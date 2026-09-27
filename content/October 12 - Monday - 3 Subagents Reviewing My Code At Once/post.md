# 3 Subagents Reviewing My Code At Once

**Date:** Mon Oct 12, 2026 · **Format:** Reel (split-screen, ~35s) · **Series:** Watch It Work · **CTA:** Comment AGENT · **Post:** post[N]
**Needs:** 🎥 face · 🖥️ screen · [RAM INPUT]

## Hook
- **On screen:** "I got 3 code reviews in 90 seconds"
- **Spoken:** "Before I commit anything now, three reviewers look at it. None of them are human."

## Script
| # | 🎥 You say | Top panel |
|---|---|---|
| 1 | Before I commit anything now, three reviewers look at it. None of them are human. | Three reviewer avatars light up: `BUGS · SCOPE · TESTS` |
| 2 | They're subagents. Separate helpers with their own instructions and their own context. | Diagram: main agent → 3 branches |
| 3 | One hunts bugs. One checks I didn't change things I shouldn't have. One looks for missing tests. | Each branch labels in turn |
| 4 | Watch. | 🖥️ triggering the review on a real diff |
| 5 | They run in parallel, and only their findings come back to my main session. | 🖥️ three summaries arriving |
| 6 | This one caught [RAM INPUT: the real finding]. | Finding card highlighted orange |
| 7 | But the bigger win is what *didn't* happen: my main session didn't fill up with 40 files of review noise. | Clean desk icon |
| 8 | Each reviewer is one small markdown file. I'll send you mine. | 🖥️ `.claude/agents/reviewer.md` open |
| 9 | Comment AGENT and you'll get the reviewer, the test-writer and the researcher. | AGENT pill pulses |

## 🎥 What you need to do
- [ ] 🖥️ **SCREEN RECORD** a real review with the reviewer subagent from the Starter Kit (plus 2 variants) on a real diff
- [ ] 🎥 **RECORD** lines 1–9
- [ ] [RAM INPUT] Beat 6: the real thing it caught. If it caught nothing, say so. That's a fine beat too ("clean, and I trust that more because three looked").
- [ ] Fact-check: whether subagents run in parallel in your current Claude Code version, and how you invoke them

## Cover
- Hook: "3 code reviews / in 90 seconds. / **None human.**"
- Illustration: three reviewer cards (BUGS · SCOPE · TESTS), each with a small finding count badge
- Bottom: "Each one is a tiny markdown file." / **"Steal mine."**

## Caption
Before I commit anything, three reviewers look at it. None of them are human.

They're subagents: small helpers, each with its own instructions and its own context.
→ one hunts bugs
→ one checks for scope creep
→ one looks for missing tests

Only their findings come back to my main session, so it doesn't fill up with review noise.

Each reviewer is a single markdown file. Comment AGENT and I'll DM you mine.

## Hashtags
#claudecode #subagents #codereview #aiagents #agenticcoding

## First comment
Source: Claude Code docs → Subagents (`.claude/agents/*.md`). The three from this video are in the Starter Kit's `.claude/agents/` folder.

## Stories (same day)
1. Screenshot of reviewer.md: "This is the whole file."
