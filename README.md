# TapKit Skills

Skills that teach AI agents how to control iPhones and navigate iOS apps.

Works with Claude Code, Codex, Cursor, OpenClaw, GitHub Copilot, and [35+ other agents](https://github.com/vercel-labs/skills).

## Install

```bash
# For any agent (Claude Code, Codex, Cursor, etc.)
npx skills add jootsing-research/jootsing-skills
```

For Claude Code plugin (includes MCP tools):

```
/plugin marketplace add jootsing-research/jootsing-skills
/plugin install tapkit@tapkit-skills
```

## Skills

### Core

| Skill | Description |
|-------|-------------|
| `tapkit` | How to use TapKit — coordinate system, screenshot loop, gestures, navigation patterns |

### App Skills

| Skill | App | What it covers |
|-------|-----|---------------|
| `hinge` | Hinge | Profile browsing, likes, roses, messaging, preferences |
| `telegram` | Telegram | Chat types, reactions, search, bots, groups, channels |
| `tiktok` | TikTok | Feed navigation, video actions, DMs, inbox, creator pages |
| `linkedin` | LinkedIn | Feed, networking, jobs, reactions, messaging |
| `uber-eats` | Uber Eats | Restaurant search, ordering, checkout, reorders |
| `twitter` | Twitter / X | Feed, compose, DMs, search, interactions |

## How Skills Work

Skills are Markdown files (`SKILL.md`) that follow the open [Agent Skills](https://agentskills.io) standard. They teach AI agents two things:

- **App knowledge** — what the app looks like (tabs, buttons, navigation patterns, gotchas)
- **Task strategy** — what to do with the app (engagement playbooks, workflows)

The agent reads the skill, then uses TapKit tools (via MCP or CLI) to execute actions on the phone.

## Requirements

- [TapKit](https://tapkit.ai) account with a connected iPhone
- TapKit CLI (`npm install -g tapkit`) or MCP server access

## Links

- [TapKit CLI](https://github.com/Jootsing-Research/tapkit-cli) — Control iPhones from the terminal
- [TapKit](https://tapkit.ai) — Get started
- [Documentation](https://docs.tapkit.ai) — Full docs
