# Watch The Agent Catch Its Own Bug

**Date:** Mon Oct 19, 2026 · **Format:** Reel (split-screen, ~35s) · **Series:** Watch It Work · **CTA:** Comment AGENT · **Post:** post[N]
**Needs:** 🎥 face · 🖥️ screen · [RAM INPUT]

## Hook
- **On screen:** "My agent caught its own bug. Here's how I made it."
- **Spoken:** "My agent just caught its own bug before I ever saw it. It wasn't luck. I set it up."

## Script
| # | 🎥 You say | Top panel |
|---|---|---|
| 1 | My agent just caught its own bug before I ever saw it. It wasn't luck. I set it up. | 🖥️ a red test turns green |
| 2 | Step one: before any code, it writes the tests. From my acceptance criteria. | Spec lines → test names |
| 3 | And they fail. On purpose. Because the feature doesn't exist yet. | 🖥️ `3 failed` in red |
| 4 | Step two: now it writes the code. And it runs the tests. | 🖥️ agent coding, then running tests |
| 5 | Two pass. One doesn't. [RAM INPUT: the real failing case, e.g. "the expired-link case"]. | `2 passed · 1 failed` (use your real numbers) |
| 6 | Here's the thing: without that test, it would've said "done". And I'd have believed it. | Chat bubble "Done ✅", crossed out |
| 7 | Instead it reads the failure, fixes it, re-runs. Green. | 🖥️ fix + all green |
| 8 | Tests first means the agent has a finish line it can't fake. | Closer |
| 9 | My test-writer subagent is in the Starter Kit. Comment AGENT. | AGENT pill |

## 🎥 What you need to do
- [ ] 🖥️ **SCREEN RECORD** a real test-first loop: test-writer writes the tests → fail → implement → one fails → fix → green
- [ ] 🎥 **RECORD** lines 1–9
- [ ] [RAM INPUT] The real failing case and real counts (beat 5). If everything passed first try, change beat 5–7 to "all green, and now I *know* it, instead of hoping."

## Cover
- Hook: "My agent caught / its own bug. / **I set it up.**"
- Illustration: a test list: 2 green ticks, 1 red cross turning green, with a small loop arrow
- Bottom: "Tests first." / **"A finish line it can't fake."**

## Caption
My AI agent caught its own bug before I ever saw it. Not luck. Setup.

1. It writes the tests first, from my acceptance criteria
2. They fail (the feature doesn't exist yet)
3. It writes the code and runs the tests
4. One fails, so it reads the failure, fixes it, and runs again
5. Green

Without that test it would've said "done", and I'd have believed it.

Tests first give your agent a finish line it can't fake.

Comment AGENT for my test-writer subagent.

## Hashtags
#claudecode #tdd #softwaretesting #aiagents #agenticcoding

## First comment
The test-writer subagent (.claude/agents/test-writer.md) is in the free Starter Kit. Comment AGENT.

## Stories (same day)
1. Poll: "Do you make your agent write tests first?" Always / Sometimes / Starting today
