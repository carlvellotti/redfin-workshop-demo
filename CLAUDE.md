# Redfin Product Team — Shared Context

This is the shared Claude Code toolkit for Redfin's product team.

## Terminology

- **RIFT** — Redfin's internal event tracking system (Real-time Interaction and Funnel Tracking)
- **LDP** — Listing Detail Page
- **MAP** — The search map view (mobile and desktop)
- **DAU** — Daily Active Users
- **GTP** — Guess the Price (engagement feature on the search map)

## Tools We Use

- **Jira + Confluence** — project tracking and documentation
- **Figma** — design files and prototyping
- **Slack** — team communication
- **RIFT/WEBEVENTS** — event data for analysis (schema: VISITOR_ID, LOGIN_ID, ENVIRONMENT, PAGE, SECTION, TARGET, ACTION, EVENT_TIMESTAMP, EVENT_DETAILS, DAY, DEVICE_CATEGORY, DEVICE_SCREEN_SIZE, HOST)

## How We Work

- Design reviews follow Ariel's framework: problem → hypothesis → V1 decisions → trade-offs
- Specs use the one-pager template in `templates/`
- Multi-perspective reviews use the personas in `personas/`
- Always come with a strong recommendation — no wishy-washy proposals

## Skills Available

Run `/` in Claude Code to see all available skills. Key ones:
- `/slack-update` — generate a team Slack post from any doc
- `/humanizer` — check writing for AI patterns
- `/leadership-review` — review through Ariel's framework
- `/competitive-news` — recent competitive intelligence
- `/experiment-check` — structured A/B test analysis
