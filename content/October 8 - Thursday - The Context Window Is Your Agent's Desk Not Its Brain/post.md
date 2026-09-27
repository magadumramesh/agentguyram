# The Context Window Is Your Agent's Desk, Not Its Brain

**Date:** Thu Oct 8, 2026 · **Format:** Carousel (8 slides, dark teal) · **Series:** Anatomy of an Agent · Part [4] · **CTA:** Save · **Post:** post[N]
**Needs:** none (fact-check only)

## Slides
**S1 · Cover.** Kicker: `ANATOMY OF AN AGENT · PART [4]`
- Hook: "Your agent gets worse the longer you chat. / **Here's why, and the 2-command fix.**"
- Illustration: a desk drawn from above. Tidy on the left ("start of session"), buried in papers on the right ("2 hours in")
- Bottom: "It's not getting tired." / **"Its desk is full."**

**S2 · The model**
- Headline: "The context window is everything the model can see right now."
- Visual: a box containing chips: CLAUDE.md · your messages · files it read · tool outputs · its own replies
- Body: "It's not memory. It's a desk. When the desk fills up, older stuff gets summarised or pushed off."

**S3 · Why long sessions degrade**
- Body: "Every file read and every test log lands on the desk. Two hours in, your original goal is buried under noise."
- Without a reset: "Why is it redoing the thing we fixed an hour ago?"

**S4 · Fix 1: /clear between tasks**
- Body: New task means a new desk. CLAUDE.md reloads automatically.
- Proof: `/clear`
- DO THIS TODAY: Finished a task? `/clear` before the next one.

**S5 · Fix 2: /compact when you're mid-task**
- Body: Summarises the conversation so far and keeps the gist.
- Proof: `/compact keep the plan and the failing test names` (*example* instruction)
- DO THIS TODAY: Compact *before* it gets slow, not after.

**S6 · Fix 3: Keep noise off the desk**
- Body: Send big searches to a subagent. It reads 40 files and only its summary lands on your desk.
- Proof: "Use a subagent to find where auth errors are handled" (*example*)

**S7 · Cheat sheet**
| Symptom | Cause | Fix |
|---|---|---|
| Forgets earlier decisions | Desk overflow | /compact, or write it in CLAUDE.md |
| Slow, rambling replies | Too much noise | /clear between tasks |
| Redoes fixed work | Goal buried | New session + handoff note |

**S8 · Closer:** SAVE THIS · "Your agent isn't getting dumber. Clear the desk." · `Anatomy · Part [4] · Next: tools & MCP`

## Caption
Your AI agent gets worse the longer you chat with it. It's not getting tired. Its desk is full.

The context window is everything the model can see right now: your messages, every file it read, every test log. Two hours in, your original goal is buried.

The fixes:
→ /clear between tasks (new task, new desk)
→ /compact mid-task, before it gets slow
→ Send big searches to a subagent so only the summary lands on your desk

Save this for the next time your agent "forgets".

## Hashtags
#claudecode #contextwindow #aiagents #llm #agenticcoding

## First comment
Source: Claude Code docs → slash commands (/clear, /compact) and subagents. Verify on the day. The "handoff note" prompt for starting fresh sessions is in the Starter Kit (comment AGENT).

## Stories (same day)
1. Quiz: "Agent forgot your earlier decision. Best fix?" /clear / /compact ✅ / yell at it
