# Signal Check / Fallback: Ask Your Agent What It's NOT Sure About

**Date:** Wed Oct 21, 2026 · **Format:** Reel (~25s) · **Series:** Signal Check → fallback Quick Fix · **CTA:** Send to a friend · **Post:** post[N]
**Needs:** 🎥 face · 🖥️ screen · 📰 news check

## 📰 NEWS SLOT
If there's a major release in the last 24h, use [signal-check-template.md](../signal-check-template.md). Otherwise post the fallback below.

---

## Fallback: Hook
- **On screen:** "The question that exposes your agent's guesses"
- **Spoken:** "There's one question I ask my AI agent after every task, and the answer is always the most useful part."

## Script
| # | 🎥 You say | Top panel |
|---|---|---|
| 1 | There's one question I ask my AI agent after every task, and the answer is always the most useful part. | `?` card pulse |
| 2 | Agents sound equally confident whether they know or they're guessing. | Two identical chat bubbles |
| 3 | So after it says done, I ask: "What are you not sure about?" | The question types on |
| 4 | And suddenly: "I assumed the timezone is UTC." "I didn't test the empty state." | 🖥️ real reply, 2–3 lines highlighted |
| 5 | Those are the exact places bugs hide. | Magnifier over the lines |
| 6 | It won't volunteer this. But it'll tell you if you ask. | `ASK` chip |
| 7 | Confidence isn't correctness. Ask for the doubts. | Closer |
| 8 | Send this to someone who ships agent code on Fridays. | Send pulse |

## 🎥 What you need to do
- [ ] 🎥 **RECORD** lines 1–8
- [ ] 🖥️ **SCREEN RECORD** asking "What are you not sure about?" after a real task, plus the real reply. Use whatever it actually says in beat 4.

## Cover
- Hook: "Ask your agent / what it's / **NOT sure about.**"
- Illustration: a chat bubble "Done ✅" with a second bubble peeling out from behind it: "…I assumed UTC"
- Bottom: "Confidence isn't correctness." / **"Ask for the doubts."**

## Caption
One question I ask my AI agent after every single task:

"What are you not sure about?"

Agents sound equally confident whether they know or they're guessing. But ask, and you get: "I assumed UTC." "I didn't test the empty state."

Those are exactly where the bugs are hiding.

Confidence isn't correctness. Ask for the doubts.

Send this to someone who ships agent code on Fridays.

## Hashtags
#aiagents #claudecode #aicoding #softwareengineering #agenticcoding

## First comment
I also put it in my CLAUDE.md "Definition of done": "Tell me what you weren't sure about." That way it happens automatically. Template: comment AGENT.

## Stories (same day)
1. Share the real screenshot of the agent's "not sure about" list
