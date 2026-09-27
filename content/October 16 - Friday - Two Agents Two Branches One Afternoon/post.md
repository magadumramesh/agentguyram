# Two Agents, Two Branches, One Afternoon

**Date:** Fri Oct 16, 2026 · **Format:** Reel (split-screen, ~40s) · **Series:** Watch It Work · **CTA:** Comment AGENT · **Post:** post[N]
**Needs:** 🎥 face · 🖥️ screen · [RAM INPUT]

## Hook
- **On screen:** "2 agents. 2 features. 0 merge conflicts."
- **Spoken:** "I had two agents building two different features at the same time, in the same repo, without them touching each other's work."

## Script
| # | 🎥 You say | Top panel |
|---|---|---|
| 1 | I had two agents building two features at the same time, in the same repo, without touching each other's work. | Two terminals side by side, both busy |
| 2 | If you run two agents in one folder, they trip over each other. Same files, same branch. | Collision icon |
| 3 | The fix is a 10-year-old git feature: worktrees. | `git worktree` chip |
| 4 | One command gives you a second copy of your repo on its own branch. | Code card: `git worktree add ../app-export -b feature/export` |
| 5 | Agent one works here on [RAM INPUT: feature A]. Agent two works there on [RAM INPUT: feature B]. | 🖥️ two windows, labelled A / B |
| 6 | I switch between them like two teammates' PRs. | 🖥️ quick cuts between the two |
| 7 | [RAM INPUT: result, e.g. "Both done by 4pm. One needed a second pass."] | Two ✓ with times |
| 8 | Here's the catch: it doubles your review load. Two agents means two diffs to actually read. | `REVIEW ×2` warning chip |
| 9 | Parallel agents aren't free. But on a Saturday with 4 hours, they're the closest thing I have to a team. | Closer |
| 10 | The worktree cheat sheet's in my Starter Kit. Comment AGENT. | AGENT pill |

## 🎥 What you need to do
- [ ] 🖥️ **SCREEN RECORD** the two worktrees + two agent sessions side by side
- [ ] 🎥 **RECORD** lines 1–10
- [ ] [RAM INPUT] The two features and the real outcome (beats 5, 7)

## Cover
- Hook: "2 agents. / 2 features. / **0 conflicts.**"
- Illustration: a git branch diagram, main splitting into two worktrees, each with an agent badge
- Bottom: "A 10-year-old git feature" / **"made this possible."**

## Caption
Two AI agents, two features, same repo, same afternoon, no collisions.

The trick is git worktrees. One command gives you a second checkout of your repo on its own branch:

git worktree add ../app-export -b feature/export

Agent A works in one folder, agent B in the other. You review them like two teammates' PRs.

The catch: it doubles your review load. Parallel agents aren't free.

Comment AGENT for my Starter Kit.

## Hashtags
#claudecode #git #aiagents #agenticcoding #buildinpublic

## First comment
Source: git docs → git-worktree. When you're done: `git worktree remove ../app-export`.

## Stories (same day)
1. Poll: "Have you ever run 2 agents at once?" Yes / No / Didn't know you could
