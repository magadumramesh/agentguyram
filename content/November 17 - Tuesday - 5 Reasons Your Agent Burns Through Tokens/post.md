# 5 Reasons Your Agent Burns Through Tokens

**Date:** Tue Nov 17, 2026 · **Format:** Carousel (9 slides) · **Series:** ACE · Day [22] · **CTA:** Save · **Post:** post[N]
**Needs:** none

## Slides
**S1 · Cover.** Kicker: `ACE AGENTIC CODING · DAY [22]`
- Hook: "Your agent bill is high because of 5 leaks, / **not because agents are expensive.**"
- Illustration: a bucket with 5 labelled holes: FILES · SESSIONS · LOGS · MEMORY · MODEL
- Bottom: "Plug the leaks," / **"keep the speed."**

**S2 · Why it matters**
- Headline: "Everything on the agent's desk gets re-read on every turn."
- Body: "So one giant file dump doesn't cost you once. It costs you on every message after it."
- Visual: one big block repeated down a timeline

**S3 · Leak 1: Reading whole files**
- Without a fix: "It read a 4,000-line file to change one function."
- Fix: point it at the function or line range; keep files small.
- DO THIS TODAY: name the exact file and function in your task.

**S4 · Leak 2: Never-ending sessions**
- Without a fix: "One session, 6 tasks, 3 hours."
- Fix: `/clear` between tasks.

**S5 · Leak 3: Noisy command output**
- Without a fix: "The full verbose test log, every run."
- Fix: quiet flags (`--silent`, `-q`), or run just the failing test.
- Proof (*example*): `pnpm test -- --run --reporter=dot`

**S6 · Leak 4: A bloated CLAUDE.md**
- Without a fix: "600 lines, loaded every session."
- Fix: keep it short; move procedures into Skills (loaded only when needed).

**S7 · Leak 5: The biggest model for everything**
- Without a fix: "Frontier model to rename a variable."
- Fix: big model to plan hard things, smaller or faster model for routine execution (check what your tool supports).

**S8 · Cheat sheet**
| Leak | Fix |
|---|---|
| Whole-file reads | Point at the function |
| Endless sessions | /clear between tasks |
| Noisy logs | Quiet flags, targeted tests |
| Bloated CLAUDE.md | Skills for procedures |
| One model for all | Match model to task |

**S9 · Closer:** SAVE THIS · "Fix leak #2 today. It's free." · `ACE · Day [22]`

## Caption
Your AI agent bill is high because of 5 leaks, not because agents are expensive.

Everything on the agent's desk gets re-read every turn, so one big dump costs you on every message after it.

1. Reading whole files → point at the function
2. Never-ending sessions → /clear between tasks
3. Noisy logs → quiet flags, run just the failing test
4. Bloated CLAUDE.md → move procedures into Skills
5. Biggest model for everything → match the model to the task

Save this. Fix #2 today, it's free.

## Hashtags
#claudecode #llm #aicosts #agenticcoding #aiagents

## First comment
Check your tool's usage/cost view (e.g. Claude Code's /cost or usage commands, verify for your version) before and after a week of this.

## Stories (same day)
1. Poll: "Do you know what your agent costs per week?" Yes / Roughly / Scared to look
