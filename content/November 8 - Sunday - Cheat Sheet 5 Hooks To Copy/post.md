# Cheat Sheet: 5 Hooks To Copy

**Date:** Sun Nov 8, 2026 · **Format:** Carousel (8 slides) · **Series:** Sunday Cheat Sheet #6 · **CTA:** Save · **Post:** post[N]
**Needs:** fact-check every snippet against the current hooks docs before posting

> All snippets are **examples**. Label them so on the slides. Test each one in a scratch repo before posting.

## Slides
**S1 · Cover.** Kicker: `SUNDAY CHEAT SHEET · #6`
- Hook: "5 hooks that make your coding agent behave. / **Copy-paste ready.**"
- Illustration: 5 lightning-bolt tiles labelled FORMAT · PROTECT · CHECK · PING · CONTEXT
- Bottom: "Paste into .claude/settings.json" / **"and they run every time."**

**S2 · 01 FORMAT: after every edit** (PostToolUse)
```
"PostToolUse": [{ "matcher": "Edit|Write",
  "hooks": [{ "type": "command",
    "command": "jq -r '.tool_input.file_path' | xargs npx prettier --write --ignore-unknown" }]}]
```

**S3 · 02 PROTECT: block edits to a folder** (PreToolUse)
```
"PreToolUse": [{ "matcher": "Edit|Write",
  "hooks": [{ "type": "command",
    "command": ".claude/hooks/protect.sh" }]}]
```
`protect.sh`: read the file path from stdin JSON; if it's under `migrations/`, print a reason to stderr and `exit 2` (blocks the edit and tells the agent why).

**S4 · 03 CHECK: tests when it stops** (Stop)
```
"Stop": [{ "hooks": [{ "type": "command",
  "command": "pnpm test -- --run --silent" }]}]
```
- Tip: fast tests only. A 10-minute suite on every stop is a punishment.

**S5 · 04 PING: notify me** (Notification)
```
"Notification": [{ "hooks": [{ "type": "command",
  "command": "osascript -e 'display notification \"Agent needs you\"'" }]}]
```
- macOS example; use `notify-send` on Linux.

**S6 · 05 CONTEXT: start every session informed** (SessionStart)
```
"SessionStart": [{ "hooks": [{ "type": "command",
  "command": "git status --short && git log --oneline -5" }]}]
```

**S7 · Rules of thumb**
- Fast (seconds, not minutes) · Quiet (short output) · In the repo (team gets them)

**S8 · Closer:** SAVE THIS · "Start with #1 and #2." · `Sunday Cheat Sheet #6`

## Caption
5 hooks that make your AI coding agent behave, copy-paste ready:

01 FORMAT: prettier after every edit
02 PROTECT: block edits to migrations/ (exit 2 = blocked + reason)
03 CHECK: fast tests when the agent stops
04 PING: a desktop notification when it needs you
05 CONTEXT: git status + recent commits at session start

Keep them fast, quiet and in the repo.

Save this and start with #1 and #2.

## Hashtags
#claudecode #automation #developertools #aiagents #agenticcoding

## First comment
Source: Claude Code docs → Hooks (events, matchers, exit-code behaviour, stdin JSON). Check the current schema before copying. #1 is in the Starter Kit (comment AGENT).

## Stories (same day)
1. Week 6 recap + "Which hook did you add?" poll
