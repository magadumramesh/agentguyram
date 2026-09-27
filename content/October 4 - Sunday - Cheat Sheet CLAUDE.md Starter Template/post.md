# Cheat Sheet: CLAUDE.md Starter Template

**Date:** Sun Oct 4, 2026 · **Format:** Carousel (7 slides) · **Series:** Sunday Cheat Sheet #1 · **CTA:** Save · **Post:** post[N]
**Needs:** none

> Tuesday explained *why*. This is the copy-paste *what*. The slides show the Starter Kit's `CLAUDE.md.template` section by section.

## Slides
**S1 · Cover.** Kicker: `SUNDAY CHEAT SHEET · #1`
- Hook: "The CLAUDE.md template I start every project with. / **Steal it.**"
- Illustration: a full-height file card, `CLAUDE.md`, with 6 section headers visible
- Bottom: "Fill in the brackets." / **"10 minutes, done."**

**S2 · Header + Commands** (code card, *template*)
```
# [Project name]
[One sentence: what it does, for whom.]

## Commands
- Install: [pnpm install]
- Test (all): [pnpm test -- --run]
- Test (one): [pnpm test -- --run path/to/file]
- Lint: [pnpm lint && pnpm typecheck]
```
- Tip strip: "The one-file test command saves the most time."

**S3 · Structure** (code card)
```
## Structure
- [src/api/]: [route handlers]
- [src/lib/]: [shared helpers. Reuse, don't duplicate]
- [src/components/]: [UI]
- [tests/]: [mirrors src/]
```

**S4 · Rules** (code card)
```
## Rules
- Plan first for anything touching 2+ files.
- Match existing patterns in the file.
- Small diffs: one concern per change.
- No new dependencies without asking.
- Run tests before saying it works. Paste output.
```

**S5 · Never + Done** (code card)
```
## Never
- Edit [migrations/] or [generated/]
- Commit .env or secrets
- Push to [main]

## Definition of done
- Tests pass (output shown)
- Lint + typecheck clean
- No unrelated files changed
- Tell me what you weren't sure about
```

**S6 · Decisions log** (code card)
```
## Decisions log
- [date]: [We use X, not Y, for Z.]
```
- Body: "Every time you correct the agent twice on the same thing, add a line here."

**S7 · Closer:** SAVE THIS · "Screenshot slides 2–6. That's the whole file." · "Tomorrow: comment AGENT to get it as a file."

## Caption
The CLAUDE.md template I start every project with. Steal it. 👇

Commands → Structure → Rules → Never → Definition of done → Decisions log.

Fill in the brackets and your AI coding agent starts every session knowing your stack, your rules, and what "done" means.

The one habit that keeps it useful: every time you correct your agent twice on the same thing, add a line to the decisions log.

Save this. Tomorrow I'll start sending the file version by DM.

## Hashtags
#claudecode #agenticcoding #aicoding #developerproductivity #aiagents

## First comment
Works in Cursor (rules files) and Codex (AGENTS.md) too: same sections, different filename. Check your tool's docs for the exact name.

## Stories (same day)
1. "Week 1 recap": 3 frames showing your top 3 posts of the week
2. "Tomorrow: comment AGENT on any post to get my free Agent Starter Kit 📩"
