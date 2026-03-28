# Contributing

Thanks for your interest in contributing to openclaw-skills.

## Adding a new skill

1. Create a folder with your skill name (lowercase, hyphenated)
2. Add a `SKILL.md` file with proper YAML frontmatter
3. Follow the [OpenClaw SKILL.md spec](https://docs.openclaw.ai/skills)
4. Open a PR with a description of what the skill does and why it's needed

## Improving existing skills

- Fix unclear instructions
- Add missing edge case handling
- Update outdated pricing or API references
- Declare env requirements in frontmatter if the skill uses credentials

## Rules

- Each skill must be a single `SKILL.md` file
- No executable code — skills are instruction sets, not scripts
- Credentials must come from environment variables, never stored to disk
- Test your skill locally before submitting
