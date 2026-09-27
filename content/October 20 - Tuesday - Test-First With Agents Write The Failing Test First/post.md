# Test-First With Agents: Write The Failing Test First

**Date:** Tue Oct 20, 2026 · **Format:** Carousel (9 slides) · **Series:** ACE · Day [18] · **CTA:** Save · **Post:** post[N]
**Needs:** none

## Slides
**S1 · Cover.** Kicker: `ACE AGENTIC CODING · DAY [18]`
- Hook: "Agents say 'done' too early. / **A failing test is how you stop that.**"
- Illustration: a 3-stage strip: RED (tests fail) → GREEN (code passes) → CHECK (you review)
- Bottom: "TDD was optional for humans." / **"For agents, it's the finish line."**

**S2 · Why it matters**
- Headline: "An agent stops when it *thinks* it's done. A test makes 'done' checkable."
- Visual: two finish lines, one dotted ("thinks"), one solid ("proven")
- Body: "It's the difference between the agent's opinion and a fact."

**S3 · Step 1: Criteria → tests**
- Body: Turn each acceptance criterion into a test before any code.
- Without it: "It tested what it built, not what I asked for."
- Proof (*example*): `it("shows 'Link expired' after 30 min")`
- DO THIS TODAY: "Write tests for these criteria only. Don't implement yet."

**S4 · Step 2: Confirm they fail, for the right reason**
- Body: A test that fails because of a typo proves nothing.
- Without it: "All red, because the import path was wrong."
- Proof (*example*): `FAIL: expected "Link expired", received undefined`

**S5 · Step 3: Lock the tests**
- Body: Tell the agent the tests are the spec. It may not edit them.
- Without it: "It 'fixed' the failing test by changing the assertion."
- Proof (*example* prompt): `Make these tests pass. Do not modify the test file.`

**S6 · Step 4: Implement + run**
- Body: Now it codes, runs and iterates until green, and pastes the output.

**S7 · Step 5: You check what tests can't**
- Body: Tests prove behaviour. You check design, naming and scope.
- DO THIS TODAY: Read the diff once, even when it's green.

**S8 · Cheat sheet**
| Step | Prompt |
|---|---|
| 1 | "Write tests for these criteria. Don't implement." |
| 2 | "Run them. Confirm they fail for the right reason." |
| 3 | "Make them pass. Don't edit the test file." |
| 4 | "Paste the final test output." |
| 5 | You: read the diff |

**S9 · Closer:** SAVE THIS · "Use it on your next bug fix: test first, then fix." · `ACE · Day [18]`

## Caption
AI agents say "done" too early. A failing test is how you stop that.

1. Turn the acceptance criteria into tests, with no code yet
2. Confirm they fail for the RIGHT reason
3. Lock them: "don't edit the test file"
4. Implement, run, iterate, paste the output
5. You read the diff for what tests can't catch

TDD was optional for humans. For agents, it's the finish line.

Save this for your next bug fix.

## Hashtags
#tdd #claudecode #softwaretesting #agenticcoding #aicoding

## First comment
The "don't modify the test file" line matters more than it looks. The #1 way agents "pass" tests is by weakening them. Test-writer subagent: comment AGENT.

## Stories (same day)
1. Slide 8 → "Screenshot the prompts 📸"
