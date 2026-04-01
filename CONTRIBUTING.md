# Contributing to the Redfin PM Toolkit

## Adding a New Skill

1. Create a folder in `.claude/skills/` with your skill name (kebab-case)
2. Add a `SKILL.md` file with:
   - A `description` in the frontmatter (one line, shown in the skill list)
   - A clear `# /skill-name` heading
   - Instructions Claude can follow
3. Test it on a real document before submitting
4. Open a PR with a description of what the skill does and an example of its output

## Updating an Existing Skill

1. Make your changes to the `SKILL.md` file
2. Test the updated skill
3. Open a PR with what you changed and why
4. Post in `#ext-product-claude-training` when merged so the team knows

## Quality Bar

Before submitting, check:

- [ ] Has a clear `description` in frontmatter
- [ ] Works for anyone on the team (no hardcoded personal context)
- [ ] Dependencies documented (if it needs an MCP like Apify, say so)
- [ ] No secrets in the file (API keys go in environment variables)
- [ ] Tested on at least one real document

## Skill Ownership

Every skill should have an owner — the person responsible for keeping it working. Add yourself as the owner in the PR description. If a skill breaks after a model update, the owner fixes it.

## Other Assets

Same process for personas, templates, and rules:
1. Create or update the file
2. Test it
3. Open a PR
4. Announce in Slack
