# Your First Skill In 10 Minutes

**Date:** Tue Oct 27, 2026 · **Format:** Carousel (9 slides) · **Series:** ACE · Day [19] · **CTA:** Save · **Post:** post[N]
**Needs:** none (fact-check only)

## Slides
**S1 · Cover.** Kicker: `ACE AGENTIC CODING · DAY [19]`
- Hook: "You keep typing the same instructions. / **Write them once as a Skill.**"
- Illustration: folder tree: `.claude/skills/release-notes/SKILL.md`
- Bottom: "One folder. One file." / **"10 minutes."**

**S2 · Why it matters**
- Headline: "A Skill loads only when it's relevant, so it doesn't clutter every session."
- Visual: CLAUDE.md (always loaded) vs Skill (loaded on demand), two lanes
- Body: "CLAUDE.md is for always-true rules. Skills are for repeatable jobs."

**S3 · Step 1: Pick a chore you've done twice**
- Body: Release notes, a PR description, a weekly report, a bug triage.
- Without it: "I wrote a Skill for something I do once a year."
- DO THIS TODAY: List 3 chores from the last 2 weeks.

**S4 · Step 2: Make the folder**
- Proof: `.claude/skills/<skill-name>/SKILL.md`
- Body: Project-level (in the repo) or personal (in your home config). Check the docs for the exact paths.

**S5 · Step 3: Write the frontmatter**
- Proof (code card):
  ```
  ---
  name: release-notes
  description: Write user-facing release notes from
    git history. Use when asked for release notes.
  ---
  ```
- Body: **The description is the trigger.** Say what it does *and when to use it*.

**S6 · Step 4: Write the steps**
- Body: Numbered, concrete, with the commands to run.
- Proof (*example*): `1. Find the last tag: git describe --tags --abbrev=0` / `2. Group into New / Improved / Fixed`

**S7 · Step 5: Add one "never" line**
- Body: The guardrail that stops the worst failure.
- Proof: `Never invent features that aren't in the commits.`
- Without it: "It 'summarised' a feature we haven't built."

**S8 · Cheat sheet**
| Part | Job | Tip |
|---|---|---|
| Folder | Where it lives | one folder per skill |
| name | ID | kebab-case |
| description | When it triggers | say WHEN to use it |
| Steps | What to do | commands, numbered |
| Never | Guardrail | the worst failure |

**S9 · Closer:** SAVE THIS · "Build one today. Tell me what it does 👇" · `ACE · Day [19]`

## Caption
You keep typing the same instructions to your AI agent. Write them once, as a Skill.

1. Pick a chore you've done twice
2. Make a folder: .claude/skills/<name>/SKILL.md
3. Frontmatter: name + description (the description is the trigger, so say WHEN to use it)
4. Numbered steps, with real commands
5. One "never" line for the worst failure

CLAUDE.md is for always-true rules. Skills are for repeatable jobs.

Save this and build one today. Tell me what yours does 👇

## Hashtags
#claudecode #agentskills #aiagents #agenticcoding #automation

## First comment
Source: Claude Code docs → Skills. Paths and frontmatter fields can change, so check yours. A full working example is in the Starter Kit (comment AGENT).

## Stories (same day)
1. Poll: "Have you built a Skill yet?" Yes / This week / What's a Skill?
