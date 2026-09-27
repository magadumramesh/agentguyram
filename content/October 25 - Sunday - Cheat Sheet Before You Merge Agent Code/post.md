# Cheat Sheet: Before You Merge Agent Code

**Date:** Sun Oct 25, 2026 · **Format:** Carousel (7 slides) · **Series:** Sunday Cheat Sheet #4 · **CTA:** Save · **Post:** post[N]
**Needs:** none
**Milestone check:** Target is 1,200 followers (stretch) or 700 (solid). Log it in `strategy/weekly-tracker.md`.

## Slides
**S1 · Cover.** Kicker: `SUNDAY CHEAT SHEET · #4`
- Hook: "The 12-point checklist I run before merging any AI-written code. / **Save it.**"
- Illustration: a clipboard with 12 checkboxes, 3 groups
- Bottom: "Takes 5 minutes." / **"Saves your weekend."**

**S2 · The agent did** (checklist card)
- ☐ Ran the tests and SHOWED the output
- ☐ Ran lint + typecheck
- ☐ Told you what it wasn't sure about

**S3 · You check: scope** (checklist card)
- ☐ Read the diff, not the chat
- ☐ No files changed that the task didn't need
- ☐ No new dependencies you didn't approve

**S4 · You check: safety** (checklist card)
- ☐ No tests deleted, skipped or weakened
- ☐ No secrets or .env values in the diff
- ☐ Error paths handled (empty, not found, offline)
- ☐ You ran it yourself once

**S5 · Red flags: stop and look closer**
- "I simplified the test to make it pass"
- Mocks replacing the thing being tested
- A big diff for a small ask
- `// TODO` where the hard part should be

**S6 · The one to never skip**
- Headline: "Read the diff, not the chat."
- Body: "The chat is the agent's story about what it did. The diff is what it actually did."

**S7 · Closer:** SAVE THIS · "Comment AGENT for the printable version." · `Sunday Cheat Sheet #4`

## Caption
The checklist I run before merging any AI-written code:

The agent did:
☐ ran tests and showed the output
☐ ran lint + typecheck
☐ said what it wasn't sure about

You check:
☐ read the diff, not the chat
☐ no unrelated files, no surprise dependencies
☐ no weakened tests, no secrets
☐ error paths handled
☐ you ran it once yourself

Red flags: "I simplified the test", mocks everywhere, a big diff for a small ask.

Save this. 5 minutes now saves your weekend.

## Hashtags
#codereview #claudecode #aicoding #softwareengineering #agenticcoding

## First comment
Printable version (verification-checklist.md) is in the free Starter Kit. Comment AGENT.

## Stories (same day)
1. **Milestone story** if you've crossed 1K: "1,000 of you 🙏 What should I build next?" plus a question box
2. Week 4 recap
