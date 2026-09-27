# Cheat Sheet: 3 Subagents You Can Copy Today

**Date:** Sun Oct 18, 2026 · **Format:** Carousel (7 slides) · **Series:** Sunday Cheat Sheet #3 · **CTA:** Save · **Post:** post[N]
**Needs:** none

## Slides
**S1 · Cover.** Kicker: `SUNDAY CHEAT SHEET · #3`
- Hook: "3 subagents I use every week. / **Full files, copy them.**"
- Illustration: three file cards: `reviewer.md` · `test-writer.md` · `researcher.md`
- Bottom: "Drop them in .claude/agents/" / **"and they're live."**

**S2 · Where they go**
- Code card: `your-repo/.claude/agents/reviewer.md` (and so on)
- Body: "Each file = frontmatter (name, description, tools) + instructions. The description is how the main agent decides when to call it."

**S3 · reviewer.md** (code card, condensed from the Starter Kit)
```
---
name: reviewer
description: Strict code reviewer. Use before committing.
tools: Read, Grep, Glob, Bash
---
Review the uncommitted diff. Report: bugs, scope creep,
test gaps, risky bits. file:line + one-line fix each.
You do not edit files.
```

**S4 · test-writer.md**
```
---
name: test-writer
description: Writes failing tests first from acceptance criteria.
tools: Read, Grep, Glob, Write, Edit, Bash
---
Match existing test conventions. One test per criterion
+ edge cases. Run them. Confirm they fail for the RIGHT
reason. You don't change app code.
```

**S5 · researcher.md**
```
---
name: researcher
description: Read-only explorer for "where/how does X work".
tools: Read, Grep, Glob
---
Answer one question. Return: answer, key files,
entry point, gotchas. Under 25 lines. Never edit.
```

**S6 · The design rule**
- Headline: "Give each one the fewest tools it needs."
- Body: "The reviewer can't edit. The researcher can't run commands. Fewer tools means fewer surprises."

**S7 · Closer:** SAVE THIS · "Comment AGENT for the full versions as files." · `Sunday Cheat Sheet #3`

## Caption
3 subagents I use every week. Full files are in the carousel:

🔍 reviewer: strict review of your diff before commit, and it can't edit anything
🧪 test-writer: writes failing tests from your acceptance criteria first
🗺️ researcher: read-only; answers "where/how does X work" without flooding your session

Drop them in .claude/agents/ and they're live.

The design rule: give each one the fewest tools it needs.

Save this, or comment AGENT for the full files.

## Hashtags
#claudecode #subagents #aiagents #agenticcoding #developertools

## First comment
Source: Claude Code docs → Subagents (file format + frontmatter fields). Check the current field names for your version.

## Stories (same day)
1. Week 3 recap + "Which subagent should I build next?" question box
