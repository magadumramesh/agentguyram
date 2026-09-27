# Watch My Agent Write My Weekly Release Notes

**Date:** Mon Oct 26, 2026 · **Format:** Reel (split-screen, ~35s) · **Series:** Watch It Work · **CTA:** Comment AGENT · **Post:** post[N]
**Needs:** 🎥 face · 🖥️ screen · [RAM INPUT]

## Hook
- **On screen:** "20-minute chore → one sentence"
- **Spoken:** "Every Friday I spent twenty minutes writing release notes for my SaaS. Now it's one sentence."

## Script
| # | 🎥 You say | Top panel |
|---|---|---|
| 1 | Every Friday I spent twenty minutes writing release notes for my SaaS. Now it's one sentence. | Timer `20:00` → `0:30` |
| 2 | [RAM INPUT: confirm the 20 minutes is real, or use your real number.] Reading commits, guessing what users would care about, rewriting jargon. | 3 chore chips |
| 3 | So I taught my agent to do it once, in a Skill. | File card `SKILL.md` |
| 4 | A Skill is a folder with instructions the agent loads only when it's relevant. | Folder icon → "loads when needed" |
| 5 | Mine says: read the git log since the last tag, group it into New, Improved, Fixed, and write it for customers, not engineers. | 🖥️ SKILL.md scrolling, 3 lines highlighted |
| 6 | Now I just say "release notes". | 🖥️ typing "write this week's release notes" |
| 7 | [RAM INPUT: the real output, e.g. "Seven commits in, four customer-facing lines out."] | 🖥️ the output |
| 8 | And the best line in the Skill: "Never invent features that aren't in the commits." | That line glows orange |
| 9 | If you do a chore twice, it should be a Skill. Mine's in the Starter Kit. Comment AGENT. | AGENT pill |

## 🎥 What you need to do
- [ ] Copy `starter-kit/.claude/skills/release-notes/` into your SaaS repo
- [ ] 🖥️ **SCREEN RECORD** asking for release notes, plus the real output
- [ ] 🎥 **RECORD** lines 1–9
- [ ] [RAM INPUT] The real time the chore took (beat 1–2) and the real output (beat 7)

## Cover
- Hook: "20-minute chore / → / **one sentence.**"
- Illustration: a `SKILL.md` card next to a neat release-notes card with New / Improved / Fixed sections
- Bottom: "Do it twice?" / **"Make it a Skill."**

## Caption
Every Friday I spent ~20 minutes writing release notes for my SaaS. Now it's one sentence.

I taught my agent once, in a Skill: a folder with instructions it loads only when relevant.

Mine says: read the git log since the last tag, group it into New / Improved / Fixed, write it for customers, not engineers. And: never invent features that aren't in the commits.

Now I just type "release notes".

If you do a chore twice, it should be a Skill. Comment AGENT and I'll send you mine.

## Hashtags
#claudecode #agentskills #aiagents #automation #buildinpublic

## First comment
Source: Claude Code docs → Skills (`.claude/skills/<name>/SKILL.md`). The release-notes skill from this video is in the Starter Kit.

## Stories (same day)
1. Question box: "What chore do you repeat every week?" (these become Sunday's cheat sheet)
