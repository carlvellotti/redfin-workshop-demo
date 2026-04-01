---
description: Run a structured experiment analysis using a monitoring doc
---

# /experiment-check

Execute a full experiment analysis based on the experiment-check.md monitoring doc.

## Instructions

1. Read the `experiment-check.md` doc in the current project. This contains:
   - The hypothesis being tested
   - Primary metric and how to calculate it
   - Secondary metrics
   - Guardrail metrics (things that should NOT get worse)
   - Data sources to reference
   - Dimensions to segment by

2. Load the referenced data files.

3. Run the analysis:
   - **Primary metric:** Calculate by variant. Include confidence interval and statistical significance.
   - **Secondary metrics:** Calculate each one. Flag any that moved unexpectedly.
   - **Guardrails:** Check each one. ALERT if any guardrail is trending in the wrong direction.
   - **Segmentation:** Break primary metric by each dimension specified. Flag segments where the effect is notably stronger or weaker.

4. Output a structured report:
   - **Top line:** Did it work? One sentence.
   - **Primary metric:** Table with control vs. treatment, delta, significance
   - **Segments:** Table showing the metric by each dimension
   - **Guardrails:** Pass/fail for each
   - **Recommendation:** Ship, iterate, or kill — with reasoning
   - **Caveats:** Sample size concerns, short time windows, anything that limits confidence

## Notes

- If `experiment-check.md` doesn't exist, use AskUserQuestions to build one interactively.
- Always state caveats honestly. Small samples = "promising signal" not "validated."
- Lead with the recommendation, not the methodology.
