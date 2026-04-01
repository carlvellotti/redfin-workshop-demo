# Redfin PM Toolkit

Shared Claude Code assets for the Redfin product team. Clone this repo and you have the team's entire AI-assisted workflow toolkit.

## Quick Start

```bash
git clone https://github.com/carlvellotti/redfin-workshop-demo
cd redfin-workshop-demo
claude
```

Claude Code automatically reads the `CLAUDE.md` and loads all skills and rules.

## What's Inside

### Skills (`.claude/skills/`)

| Skill | Type | What it does |
|-------|------|-------------|
| `/slack-update` | Generate | Turns any doc into a formatted Slack team update |
| `/humanizer` | Review | Checks writing for AI patterns and rewrites them |
| `/competitive-news` | Research | Finds recent news about your competitors |
| `/experiment-check` | Workflow | Runs a structured A/B test analysis from a monitoring doc |
| `/leadership-review` | Review | Reviews docs through Ariel's design review framework |

### Rules (`.claude/rules/`)

- `data-privacy.md` — PII handling, aggregation minimums, data safety
- `response-style.md` — Communication standards (lead with recommendation, no hedging)

### Personas (`personas/`)

- `engineering-lead.md` — Technical feasibility and scope review
- `ariel-cpdo.md` — Ariel's design review and communication framework
- `ux-researcher.md` — User evidence and interaction design review

### Templates (`templates/`)

- `one-pager.md` — Feature spec template (problem, hypothesis, solution, metrics)
- `slack-update.md` — Slack post format
- `email-summary.md` — Executive email template

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to add skills, update existing ones, and the quality bar for shared assets.

## Built with

Created during the [Redfin x Full Stack PM](https://fullstackpm.com/redfin) Claude Code workshop.
