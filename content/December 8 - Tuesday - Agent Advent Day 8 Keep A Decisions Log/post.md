# Agent Advent Day 8: Keep A Decisions Log

**Date:** Tue Dec 8, 2026 · **Format:** Carousel (6 slides) · **Series:** Agent Advent · Day 8/24 · **CTA:** Save · **Post:** post[N]
**Needs:** none

## Slides
**S1 · Cover.** Kicker: `AGENT ADVENT · DAY 8/24`
- Hook: "Your agent keeps undoing decisions you made last month. / **Write them down where it reads.**"
- Illustration: a small log card with dated one-liners, pinned to a CLAUDE.md file
- Bottom: "Decided once." / **"Remembered every session."**

**S2 · Why**
- Body: "The agent never saw the discussion where you chose Postgres over Mongo, or server actions over API routes. So it 'helpfully' suggests the other one. Every time."

**S3 · The format** (code card, *example*)
```
## Decisions log (newest first)
- 2026-11-20: Server actions, not API routes, for forms.
- 2026-10-02: Dates stored UTC, shown in user's TZ.
- 2026-09-14: No ORMs. Raw SQL via lib/db.ts.
```

**S4 · The rule for adding one**
- Headline: "Corrected the agent twice on the same thing? That's a decision. Log it."

**S5 · Bonus**
- Body: "Your future self (and teammates) get the same benefit. It's an ADR log for people who don't write ADRs."

**S6 · Closer:** SAVE THIS · "Door 8 ✅" · grid

## Caption
🎄 Agent Advent, Day 8/24: keep a decisions log.

Your agent keeps suggesting things you ruled out months ago. It never saw that discussion.

Add a "Decisions log" to CLAUDE.md, newest first:
- 2026-11-20: Server actions, not API routes, for forms
- 2026-10-02: Dates stored UTC, shown in user's TZ

The rule: corrected it twice on the same thing? That's a decision. Log it.

Save this.

## Hashtags
#claudecode #agentadvent #softwarearchitecture #aiagents #adventcalendar

## First comment
The CLAUDE.md template in the Starter Kit already has a Decisions log section. Comment AGENT.

## Stories (same day)
1. Door 8 ✅
