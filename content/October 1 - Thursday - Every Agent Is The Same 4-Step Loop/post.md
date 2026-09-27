# Every Agent Is The Same 4-Step Loop

**Date:** Thu Oct 1, 2026 · **Format:** Carousel (8 slides, dark teal "Anatomy" style) · **Series:** Anatomy of an Agent · Part [3] · **CTA:** Save · **Post:** post[N]
**Needs:** none (fact-check only)

## Slides
**S1 · Cover.** Kicker: `ANATOMY OF AN AGENT · PART [3]`
- Hook: "Claude Code, Cursor, Codex, Devin. / **Same 4-step loop underneath.**"
- Illustration: a circular loop diagram: THINK → ACT → OBSERVE → REPEAT, with a small "STOP?" diamond
- Bottom: "Understand the loop," / **"and every agent makes sense."**

**S2 · Why it matters**
- Headline: "A chatbot answers once. An agent keeps going until the job's done."
- Visual: side by side. Chatbot: `question → answer`. Agent: `goal → loop ×N → result`
- Body: "That loop is why agents can fix a bug across 6 files, and also why they sometimes spiral."

**S3 · Step 1: THINK**
- Body: The model reads the goal plus everything so far, and decides the next single step.
- Without a clear goal: "It 'improves' 12 things you didn't ask for."
- Proof (*illustrative*): `"I should find where the login error is thrown."`

**S4 · Step 2: ACT**
- Body: It calls a tool: read a file, run a command, search, edit.
- The key idea: **the model doesn't touch your computer. Tools do.** The model only asks to use them.
- Proof (*illustrative*): `tool: grep  args: "InvalidToken" src/`

**S5 · Step 3: OBSERVE**
- Body: The tool's result goes back into the context: file contents, test output, errors.
- Why it matters: "This is why a failing test is gold. It's a real signal the agent can react to."
- Proof (*illustrative*): `src/auth.ts:42 throw new InvalidToken()`

**S6 · Step 4: REPEAT (or STOP)**
- Body: Loop until the goal is met, it needs you, or it runs out of room.
- The failure mode: "No clear 'done' means no clean stop. That's when it spirals."
- DO THIS TODAY: Give every task a "done when…" line.

**S7 · Cheat sheet**
| Step | What happens | You control it with |
|---|---|---|
| Think | Picks next step | A clear goal |
| Act | Calls a tool | Permissions |
| Observe | Reads results | Tests & logs |
| Repeat/Stop | Loops or finishes | A "done when" |

**S8 · Closer:** SAVE THIS · "Next time your agent goes off the rails, ask: which step broke?" · `Anatomy · Part [3] · Next: the context window`

## Caption
Claude Code, Cursor, Codex, Devin: different products, same loop underneath.

1. THINK: decide the next single step
2. ACT: call a tool (read, run, search, edit)
3. OBSERVE: read the result
4. REPEAT until done, or stop

The model never touches your computer directly. Tools do. The model just asks to use them.

Once you see the loop, agent failures stop being mysterious. Bad goal? Step 1. No tests? Step 3. No "done"? It never stops.

Save this for the next time your agent goes off the rails.

## Hashtags
#aiagents #agenticai #claudecode #llm #howaiworks

## First comment
Further reading: Anthropic's "Building effective agents" post and the Claude Code docs "How Claude Code works". Both describe this agent loop (verify the titles on the day).

## Stories (same day)
1. Quiz: "Which step fails when your agent says 'done' but nothing works?" Think / Act / Observe ✅ / Repeat
