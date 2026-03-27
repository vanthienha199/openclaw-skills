# openclaw-skills

10 production-ready OpenClaw skills for developers. Cost tracking, deployment, translation, presentations, job search, and more.

**No API keys required** for most skills. No external dependencies. Just drop into your OpenClaw workspace.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-10-orange.svg)](#skills)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-compatible-green.svg)](https://openclaw.ai)

## Skills

| Skill | What it does | Tags |
|-------|-------------|------|
| [smart-cost-tracker](smart-cost-tracker/) | Track per-message API spending. Budget alerts, daily reports, cost trends. | cost, tokens, budget |
| [translate](translate/) | Translate text and files between any languages. Preserves formatting. | language, i18n |
| [slide-deck](slide-deck/) | Generate reveal.js HTML presentations from markdown or text. | slides, presentation |
| [deploy-kit](deploy-kit/) | Deploy to Vercel, Netlify, or Fly.io. Auto-detects framework. | deploy, devops |
| [job-hunter](job-hunter/) | Resume builder, cover letters, interview prep, application tracker. | career, resume |
| [supabase](supabase/) | Query, insert, update, delete. RLS policies, auth, storage. | database, postgres |
| [meeting-notes](meeting-notes/) | Transcript to structured notes with action items and owners. | meetings, notes |
| [project-kickstart](project-kickstart/) | Scaffold Next.js, React, Python, FastAPI, Express projects in seconds. | scaffold, starter |
| [social-poster](social-poster/) | Draft cross-platform posts for Twitter, LinkedIn, Reddit, Dev.to, HN. | social, marketing |
| [figma-bridge](figma-bridge/) | Extract design tokens, components, and assets from Figma files. | design, figma, css |

## Install

### Option 1: Copy individual skills
```bash
git clone https://github.com/vanthienha199/openclaw-skills.git
cp -r openclaw-skills/smart-cost-tracker ~/.openclaw/skills/
```

### Option 2: Copy all skills
```bash
git clone https://github.com/vanthienha199/openclaw-skills.git
cp -r openclaw-skills/*/ ~/.openclaw/skills/
```

### Option 3: ClawHub (individual skills)
```bash
npx clawhub@latest install vanthienha199/smart-cost-tracker
npx clawhub@latest install vanthienha199/translate
# ... etc
```

Then restart your OpenClaw session (`/reset` in TUI) to pick up new skills.

## Requirements

- OpenClaw 2026.3.x or later
- No external dependencies for most skills
- `supabase` needs a Supabase project URL + anon key
- `figma-bridge` needs a Figma Personal Access Token
- `deploy-kit` needs the platform CLI (vercel/netlify/fly) installed
- `slide-deck` outputs self-contained HTML using reveal.js CDN

## Why These Skills?

These fill gaps in the OpenClaw ecosystem:

- **smart-cost-tracker** — the existing Model Usage skill only shows raw numbers. This gives you budget alerts, per-task cost, and spending trends.
- **translate** — 114 people requested i18n support on the OpenClaw repo. No good translation skill existed.
- **slide-deck** — the Chinese presentation skill has 19K+ downloads. No English version existed.
- **supabase** — 75K+ GitHub stars, millions of developers. Zero OpenClaw integration until now.
- **figma-bridge** — Figma MCP server has 14K GitHub stars. Nothing on ClawHub.
- **deploy-kit** — no Vercel, Netlify, or Fly.io skill existed on ClawHub.

## Contributing

PRs welcome. Each skill is a folder with a single `SKILL.md` file following the [OpenClaw SKILL.md spec](https://docs.openclaw.ai/skills).

If you build a skill that fills a gap, open a PR.

## License

MIT

## Author

Built by [Ha Le](https://github.com/vanthienha199) — University of Central Florida
