# Break Big Features Into Agent-Sized Tasks

**Date:** Tue Nov 24, 2026 · **Format:** Carousel (9 slides) · **Series:** ACE · Day [23] · **CTA:** Save · **Post:** post[N]
**Needs:** none

## Slides
**S1 · Cover.** Kicker: `ACE AGENTIC CODING · DAY [23]`
- Hook: "'Build the billing page' is too big for one agent session. / **Here's how to slice it.**"
- Illustration: one big block "BILLING PAGE" sliced into 4 smaller labelled blocks
- Bottom: "Big asks fail quietly." / **"Small asks ship."**

**S2 · Why it matters**
- Headline: "An agent-sized task fits in one session, has one outcome, and can be checked in one command."
- Visual: 3 ticks: ONE SESSION · ONE OUTCOME · ONE CHECK

**S3 · Slice 1: by layer**
- Body: data → logic → UI. Each can be tested on its own.
- Example (*illustrative*): `1. Invoice model + migration` · `2. Pricing calc + tests` · `3. Billing page UI`

**S4 · Slice 2: by user path**
- Body: happy path first, edge cases next.
- Example: `1. Pay with a saved card` · `2. Card declined` · `3. No card on file`

**S5 · Slice 3: walking skeleton**
- Body: an ugly end-to-end version first, then improve each part.
- Why: you find integration problems on day one, not day five.

**S6 · The size test**
- Too big if: it touches 6+ files · you can't write a "done when" · it needs 2 kinds of test
- Too small if: the setup takes longer than the task

**S7 · Order matters**
- Body: Do the riskiest slice first. If it doesn't work, you've wasted one session, not five.

**S8 · Cheat sheet**
| Slice by… | Best when |
|---|---|
| Layer | Clear architecture |
| User path | Lots of edge cases |
| Walking skeleton | Many moving parts |
| **Always** | Riskiest slice first |

**S9 · Closer:** SAVE THIS · "Every good engineer slices work. Now your agent needs you to." · `ACE · Day [23]`

## Caption
"Build the billing page" is too big for one AI agent session. Slice it.

An agent-sized task = one session, one outcome, one check.

3 ways to slice:
→ by layer: data → logic → UI
→ by user path: happy path first, then edge cases
→ walking skeleton: ugly end-to-end first, then improve

Too big if it touches 6+ files or you can't write a "done when".
Always do the riskiest slice first.

Save this.

## Hashtags
#claudecode #agenticcoding #softwareengineering #productmanagement #aiagents

## First comment
This is exactly how I split this week's build (Part 1 was yesterday, Part 2 is Friday).

## Stories (same day)
1. Your real task split from Monday's build as a story frame
