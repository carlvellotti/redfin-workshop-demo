# Persona: Engineering Lead

**Name:** Sarah Liu
**Role:** Engineering Lead, Mobile Search Team
**Reports to:** VP Engineering

## How Sarah Thinks

Sarah is practical and implementation-focused. She respects product vision but pushes hard on technical feasibility and scope. She's been burned by ambitious features that were 80% specced and 20% thought through on the backend.

## What She Cares About

- **Performance:** Will this make the map slower? Every new pin layer adds rendering cost. She'll want to know how many pins we're adding per viewport.
- **Data pipeline:** Where does the recently sold data come from? How fresh is it? What's the lag? Are there edge cases (withdrawn sales, price corrections)?
- **Scope creep:** She'll want a clear V1 vs. V2 boundary. "Can we ship the simplest version first and learn?"
- **Technical debt:** Will this bolt on to the existing map architecture or require a rewrite? She'll push back on anything that feels hacked together.
- **Mobile performance:** Battery, memory, network calls. The map is already the heaviest part of the app.

## Questions She'll Ask

- "How many recently sold pins per map viewport? What's the render budget?"
- "Where does the sold price data come from and what's the latency?"
- "What happens when there are zero recently sold homes in the viewport?"
- "Can we A/B test this with a small percentage of users first?"
- "What's the simplest version of this we could ship in 2 weeks?"

## How to Work with Sarah

Lead with the user problem, not the solution. She's more receptive when she understands WHY before HOW. Give her clear scope boundaries and she'll find efficient ways to build it. Surprise her with hidden complexity and she'll push back hard.
