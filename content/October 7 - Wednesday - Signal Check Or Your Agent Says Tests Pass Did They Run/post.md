# Signal Check / Fallback: "Tests Pass." Did They Run?

**Date:** Wed Oct 7, 2026 · **Format:** Reel (~25s) · **Series:** Signal Check → fallback Quick Fix · **CTA:** Send to a friend · **Post:** post[N]
**Needs:** 🎥 face · 🖥️ screen · 📰 news check

## 📰 NEWS SLOT
If there's a major agent/model release in the last 24h, use [signal-check-template.md](../signal-check-template.md). Otherwise post the fallback below.

---

## Fallback: Hook
- **On screen:** "'All tests pass ✅' Did they, though?"
- **Spoken:** "Your agent just told you all tests pass. Did it actually run them?"

## Script
| # | 🎥 You say | Top panel |
|---|---|---|
| 1 | Your agent just told you all tests pass. Did it actually run them? | Chat bubble: `All tests pass ✅` |
| 2 | Sometimes it did. Sometimes it predicted they would. | Two cards: `RAN` vs `PREDICTED` |
| 3 | Those look identical in the chat. | The two cards overlap, same look |
| 4 | So I added one line to every task: "Run the tests and paste the actual output." | Line types on |
| 5 | Now I get this instead. | 🖥️ real test output scrolling: pass counts, timing |
| 6 | Real numbers. Real failures, when there are any. | `12 passed · 1 failed` highlight (*example*) |
| 7 | Don't trust the summary. Trust the output. | Big closer |
| 8 | Send this to whoever merges AI code on your team. | Send pulse |

## 🎥 What you need to do
- [ ] 🎥 **RECORD** lines 1–8
- [ ] 🖥️ **SCREEN RECORD** 5s of an agent running your real test suite and pasting the output

## Cover
- Hook: "'All tests pass ✅' / **Did they run?**"
- Illustration: a chat bubble "All tests pass ✅" next to an empty terminal with a blinking cursor
- Bottom: "Don't trust the summary." / **"Trust the output."**

## Caption
"All tests pass ✅"

Sometimes your AI agent ran them. Sometimes it predicted they would pass. In the chat, those two look identical.

The one-line fix: add "Run the tests and paste the actual output" to every task.

Don't trust the summary. Trust the output.

Send this to whoever merges AI-written code on your team.

## Hashtags
#claudecode #aicoding #softwaretesting #agenticcoding #aiagents

## First comment
The "Prove it" prompt and a full pre-merge checklist are in the Agent Starter Kit. Comment AGENT.

## Stories (same day)
1. Poll: "Has an agent ever told you tests passed when they didn't?" Yes 😩 / Not yet
