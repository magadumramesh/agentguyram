# I Went To Bed. My Agent Opened A PR.

**Date:** Fri Nov 6, 2026 · **Format:** Reel (split-screen, ~40s) · **Series:** Watch It Work · **CTA:** Comment AGENT · **Post:** post[N]
**Needs:** 🎥 face (night + morning) · 🖥️ screen · [RAM INPUT]

> Pick an **L4 task** from Thursday's post: small, well tested, easy to revert (e.g. fix all lint warnings in one folder, or add missing tests for one module). Run it headless (`claude -p "…"`), or with your tool's equivalent, on a branch.

## Hook
- **On screen:** "11 PM: gave my agent a task. 7 AM: 👀"
- **Spoken:** "At 11 PM I gave my agent one task and went to bed. Here's what was waiting at 7 AM."

## Script
| # | 🎥 You say | Top panel |
|---|---|---|
| 1 | At 11 PM I gave my agent one task and went to bed. Here's what was waiting at 7 AM. | Clock `11:00 PM` 🌙 |
| 2 | The task: [RAM INPUT: e.g. "add missing tests for the billing module"]. Small, boring, easy to undo. | Task card |
| 3 | No chat window. One command, running in the background, on its own branch. | Code card: `claude -p "<task + done-when>"` (*example*) |
| 4 | The rules: tests must pass, don't touch app code, open a PR when done. | 3 rule chips |
| 5 | 🎥 (morning, coffee) Okay. Let's see. | Clock `7:00 AM` ☀️ |
| 6 | [RAM INPUT: the real result, e.g. "A PR. 14 new tests. All green."] | 🖥️ the PR |
| 7 | [RAM INPUT: the honest catch, e.g. "Two of them test nothing useful. I deleted them."] | Orange "catch" card |
| 8 | That's the deal with overnight agents: small task, strict rules, and you still review in the morning. | 3 steps |
| 9 | My "done when" template is in the Starter Kit. Comment AGENT. | AGENT pill |

## 🎥 What you need to do
- [ ] 🎥 **RECORD** beats 1–4 at night (dim, real setting), then beats 5–9 in the morning
- [ ] 🖥️ **SCREEN RECORD** kicking off the headless run, then the PR in the morning
- [ ] [RAM INPUT] The task, the result and the honest catch (beats 2, 6, 7)
- [ ] Fact-check the headless flag/syntax in the current docs

## Cover
- Hook: "I went to bed. / My agent / **opened a PR.**"
- Illustration: a moon → sun transition with a PR card "✓ checks passed" in between
- Bottom: "Small task. Strict rules." / **"Still reviewed it."**

## Caption
11 PM: I gave my AI agent one task and went to bed.
7 AM: [RAM INPUT: result].

The setup:
→ a small, boring, reversible task
→ headless: one command, no chat window, its own branch
→ rules: tests pass, don't touch app code, open a PR

The catch: [RAM INPUT].

Overnight agents work when the task is small, the rules are strict, and you still review in the morning.

Comment AGENT for my "done when" template.

## Hashtags
#claudecode #automation #aiagents #buildinpublic #agenticcoding

## First comment
Source: Claude Code docs → headless mode / CLI (`-p`). Exact command: [RAM INPUT]. Don't do this on a vague task (see the Halloween post 👻).

## Stories (same day)
1. The night before: "Leaving my agent a task tonight 🌙 Results tomorrow"
