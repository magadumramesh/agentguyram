# Signal Check / Fallback: 3 Things I Never Let An Agent Do Alone

**Date:** Wed Sep 30, 2026 · **Format:** Reel (split-screen face, ~30s) · **Series:** Signal Check → fallback Quick Fix · **CTA:** Send to a friend · **Post:** post[N]
**Needs:** 🎥 face · 📰 news check

## 📰 NEWS SLOT: check this morning
If a **major** agent/model release landed in the last 24h (OpenAI, Anthropic, Google, a big open-source launch), make a Signal Check Reel instead, using the template in **[signal-check-template.md](../signal-check-template.md)**. Otherwise post the fallback below.

---

## Fallback: Hook
- **On screen:** "3 things I never let an AI agent do alone"
- **Spoken:** "There are three things I never let an AI agent do without me. Even the good ones."

## Script
| # | 🎥 You say | Top panel |
|---|---|---|
| 1 | There are three things I never let an AI agent do without me. Even the good ones. | Title card, `3` count-up |
| 2 | One: push to main. | `01 · git push origin main` struck through |
| 3 | Agents are great at writing code. But they don't know it's Friday at 5 and you're about to sign off. | Clock icon `FRI 5:00 PM` |
| 4 | So they work on a branch, and I merge. | `branch → PR → me → main` |
| 5 | Two: anything that touches secrets. | `02 · .env 🔒` |
| 6 | I block the agent from reading my .env file in settings. It can't leak what it never sees. | Code card (*example*): `"deny": ["Read(./.env)"]` |
| 7 | Three: deleting data. Migrations, drops, "cleanup" scripts. | `03 · DROP TABLE` in red |
| 8 | It can write the migration. I read every line before it runs. | Checklist ✓ "read before run" |
| 9 | Speed is the agent's job. Brakes are mine. | Big closing line |
| 10 | Send this to the teammate who just said "let the AI handle it". | Send icon pulse |

## 🎥 What you need to do
- [ ] 🎥 **RECORD** lines 1–10.
- [ ] Fact-check: the `permissions.deny` syntax in the current Claude Code settings docs.

## Cover
- Hook: "3 things I never / let an AI agent / **do alone.**"
- Illustration: three red "stop" tiles: `push to main` · `.env` · `DROP TABLE`
- Bottom: "Speed is the agent's job." / **"Brakes are yours."**

## Caption
Three things I never let an AI coding agent do without me, even the good ones:

1. Push to main. It works on a branch, and I merge.
2. Touch secrets. I deny it read access to .env in settings.
3. Delete data. It can write the migration; I read every line before it runs.

Speed is the agent's job. Brakes are yours.

Send this to the teammate who just said "let the AI handle it."

## Hashtags
#aiagents #claudecode #agenticcoding #devops #softwareengineering

## First comment
Source: Claude Code docs → Settings → Permissions (allow/deny rules). The full example config is in my free Agent Starter Kit, so comment AGENT from next week and I'll DM it.

## Stories (same day)
1. Poll: "Would you let an agent push to main?" Never / With tests / Already do 😬
