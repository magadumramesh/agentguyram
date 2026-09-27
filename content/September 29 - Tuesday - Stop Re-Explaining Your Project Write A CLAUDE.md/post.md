# Stop Re-Explaining Your Project. Write A CLAUDE.md.

**Date:** Tue Sep 29, 2026 · **Format:** Carousel (9 slides, dark current standard) · **Series:** ACE · Day [15] · **CTA:** Save · **Post:** post[N]
**Needs:** none (fact-check only)

## Slides
**S1 · Cover.** Kicker: `ACE AGENTIC CODING · DAY [15]`
- Hook: "Your agent forgets your project every session. / **One file fixes that.**"
- Illustration: a file card `CLAUDE.md` with 4 labelled rows: Commands · Structure · Rules · Never
- Bottom: "Explain it once." / **"It reads it every time."**

**S2 · Why it matters**
- Headline: "Claude Code loads CLAUDE.md into every session automatically."
- Visual: timeline `session starts → reads CLAUDE.md → your first prompt`
- Receipt line: "Source: Claude Code docs → Memory" (verify wording on the day)
- Body: "No file means your first 5 minutes go to re-explaining your stack. Every. Single. Time."

**S3 · Tool 1: Commands**
- Body: The exact commands to install, test and lint.
- Without it: "It ran `npm test`. We use pnpm. Nothing ran."
- Proof (code card, *example*):
  ```
  ## Commands
  - Test: pnpm test -- --run
  - Lint: pnpm lint && pnpm typecheck
  ```
- DO THIS TODAY: Paste your real test command in.

**S4 · Tool 2: Structure**
- Body: The 4–5 folders that matter, and what lives in each.
- Without it: "It made a new `utils/`. We already had `lib/`."
- Proof (*example*): `- src/lib: shared helpers. Reuse, don't duplicate.`
- DO THIS TODAY: List the folders a new hire would ask about.

**S5 · Tool 3: Rules**
- Body: What you'd tell a new teammate on day one.
- Without it: "It pulled in a whole library for a one-liner."
- Proof (*example*): `- No new dependencies without asking` / `- Small diffs, one concern per change`
- DO THIS TODAY: Write 3 rules you've repeated in chat this week.

**S6 · Tool 4: Never**
- Body: The hard lines. Short and absolute.
- Without it: "It 'tidied up' a migration file." (*illustrative*)
- Proof (*example*): `- Never edit migrations/` / `- Never commit .env` / `- Never push to main`
- DO THIS TODAY: Add your 3 scariest "please don't".

**S7 · Tool 5: Keep it short**
- Body: It's read every session, so every line costs context. Delete what's stale.
- Without it: "A 600-line CLAUDE.md nobody (including the agent) follows."
- Proof: `/init` drafts a first version from your repo. Then cut it in half.
- DO THIS TODAY: Run `/init`, then delete anything obvious.

**S8 · Cheat sheet**
| Section | What goes in | Example |
|---|---|---|
| Commands | install / test / lint | `pnpm test -- --run` |
| Structure | 4–5 key folders | `src/lib: helpers` |
| Rules | day-one teammate advice | small diffs |
| Never | hard lines | no push to main |
| Done | how "finished" is proven | tests shown |

**S9 · Closer:** SAVE THIS pill · "Write yours before your next session. 10 minutes." · `ACE · Day [15] · Next: the 5-line task spec`

## Caption
Your AI coding agent forgets your whole project every time you start a new session.

So you re-explain the stack. The test command. "Please don't touch that folder." Again.

Claude Code reads a file called CLAUDE.md at the start of every session. Write it once and those 5 minutes come back, every session.

The 5 sections I put in mine are in the carousel, plus a cheat sheet on the last slide.

Save this for your next session. It takes 10 minutes to write.

## Hashtags
#claudecode #agenticcoding #aicoding #aiagents #developertools

## First comment
Sources: Claude Code docs → "Memory" / CLAUDE.md (docs.claude.com / code.claude.com). Cursor and Codex have equivalents (rules files / AGENTS.md), so the same 5 sections work there.

## Stories (same day)
1. Slide 8 (the cheat sheet): "Screenshot this 📸"
2. Quiz: "Where does Claude Code read project instructions from?" CLAUDE.md ✅ / README.md / .env
