# Signal Check / Fallback: Stop Pasting Errors. Let The Agent Read The Logs.

**Date:** Wed Oct 14, 2026 · **Format:** Reel (~25s) · **Series:** Signal Check → fallback Quick Fix · **CTA:** Send to a friend · **Post:** post[N]
**Needs:** 🎥 face · 🖥️ screen · 📰 news check

## 📰 NEWS SLOT
If there's a major release in the last 24h, use [signal-check-template.md](../signal-check-template.md). Otherwise post the fallback below.

---

## Fallback: Hook
- **On screen:** "Stop copy-pasting errors into your agent"
- **Spoken:** "If you're still copy-pasting error messages into your AI agent, you're doing its job for it."

## Script
| # | 🎥 You say | Top panel |
|---|---|---|
| 1 | If you're still copy-pasting error messages into your AI agent, you're doing its job for it. | Ctrl+C / Ctrl+V keycaps, struck out |
| 2 | You copy the last 10 lines. But the real cause was line 3 of 200. | Log scroll; line 3 glows |
| 3 | Coding agents can run commands. So let them. | Terminal card |
| 4 | "Run the dev server, reproduce the bug, and read the full output." | Prompt types on |
| 5 | Now it sees everything: the stack trace, the warning you scrolled past, the env var that's missing. | 🖥️ agent reading full output, 3 highlights |
| 6 | And after it fixes it, it runs it again to check. | `run → fix → run ✓` |
| 7 | Stop being the messenger. Let it read the logs. | Closer |
| 8 | Send this to the friend who pastes screenshots of errors. | Send pulse |

## 🎥 What you need to do
- [ ] 🎥 **RECORD** lines 1–8
- [ ] 🖥️ **SCREEN RECORD** an agent running a command, reading a failure, fixing it and re-running (5–8s, sped up)

## Cover
- Hook: "Stop pasting / errors into / **your agent.**"
- Illustration: a clipboard with a crossed-out error snippet → a terminal with the full log and 3 highlighted lines
- Bottom: "You copied line 197." / **"The bug was on line 3."**

## Caption
If you're still copy-pasting error messages into your AI coding agent, you're doing its job for it.

You paste the last 10 lines. The real cause was line 3 of 200.

Instead: "Run it, reproduce the bug, read the full output, fix it, run it again."

Stop being the messenger. Let it read the logs.

Send this to the friend who sends screenshots of errors 😅

## Hashtags
#claudecode #debugging #aicoding #agenticcoding #aiagents

## First comment
Tip: allowlist your safe run commands (test, dev server, lint) so you're not clicking "allow" every time. The example settings file is in the Starter Kit (comment AGENT).

## Stories (same day)
1. Poll: "How do you give your agent errors?" Paste / Screenshot / It reads them itself
