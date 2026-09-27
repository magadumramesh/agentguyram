# When A Subagent Helps, And When It's A Waste

**Date:** Tue Oct 13, 2026 · **Format:** Carousel (9 slides) · **Series:** ACE · Day [17] · **CTA:** Save · **Post:** post[N]
**Needs:** none (fact-check only)

## Slides
**S1 · Cover.** Kicker: `ACE AGENTIC CODING · DAY [17]`
- Hook: "Subagents make some tasks faster and others slower. / **Here's the line.**"
- Illustration: a two-column card, `USE ONE ✓` (3 icons) vs `SKIP IT ✗` (3 icons)
- Bottom: "It's not about power." / **"It's about what lands on your desk."**

**S2 · What a subagent is**
- Headline: "A separate agent with its own instructions, its own tools and its own context window."
- Visual: main session box; a subagent box beside it; only a small "summary" arrow flows back
- Body: "It does the messy work elsewhere and hands you the conclusion."

**S3 · USE: big searches**
- Body: "Find everywhere we handle auth errors": 40 files read, 10 lines returned.
- Without it: "My session filled with file dumps and got slow."
- DO THIS TODAY: Route "where/how does X work" questions to a researcher subagent.

**S4 · USE: independent reviews**
- Body: Reviews want a fresh eye, not a context that already believes the code is right.
- Without it: "It reviewed its own code and loved it."

**S5 · USE: parallel, separate jobs**
- Body: Tests for module A while it docs module B. No shared state, so no conflicts.

**S6 · SKIP: tiny tasks**
- Body: A one-line fix doesn't need a helper. Spinning one up costs more than it saves.
- Without this rule: "Three agents, one typo."

**S7 · SKIP: tightly coupled work**
- Body: If step 2 needs every detail of step 1, keep it in one context. Summaries drop details.
- Without this rule: "The subagent fixed the bug, but in the old version of the file."

**S8 · Cheat sheet**
| Task | Subagent? | Why |
|---|---|---|
| "Where is X handled?" | ✅ | Keeps noise off your desk |
| Code review | ✅ | Fresh eyes |
| Independent parallel jobs | ✅ | Speed |
| One-line fix | ❌ | Overhead |
| Step-by-step dependent work | ❌ | Summaries lose detail |

**S9 · Closer:** SAVE THIS · "Ask: do I need the answer or the process?" · `ACE · Day [17]`

## Caption
Subagents make some tasks faster and others slower. The line is simple: do you need the process, or just the answer?

✅ Use one for big codebase searches, independent code reviews, and parallel jobs that don't share state.
❌ Skip it for tiny fixes (the overhead beats the gain) and tightly coupled step-by-step work (summaries drop the details you need).

Save this before you spin up five agents for a typo.

## Hashtags
#claudecode #subagents #agenticcoding #aiagents #aicoding

## First comment
Source: Claude Code docs → Subagents. My three ready-made subagents (reviewer, test-writer, researcher) are in the Starter Kit. Comment AGENT.

## Stories (same day)
1. Poll: "How many subagents do you use?" 0 / 1–2 / 3+ / what's a subagent
