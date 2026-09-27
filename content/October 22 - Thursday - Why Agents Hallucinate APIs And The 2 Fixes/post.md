# Why Agents Hallucinate APIs (And The 2 Fixes)

**Date:** Thu Oct 22, 2026 · **Format:** Carousel (8 slides, dark teal) · **Series:** Anatomy of an Agent · Part [6] · **CTA:** Save · **Post:** post[N]
**Needs:** none (fact-check only)

## Slides
**S1 · Cover.** Kicker: `ANATOMY OF AN AGENT · PART [6]`
- Hook: "Your agent called a function that doesn't exist. / **Here's why, and 2 fixes.**"
- Illustration: a code card with `client.users.fetchAll()` and a red squiggle "not a real method" (*illustrative*)
- Bottom: "It's not lying." / **"It's pattern-matching."**

**S2 · Why it happens**
- Headline: "Models learn what code *usually* looks like, not what *your* version of a library contains."
- Visual: a blurred average of 1,000 code snippets → one plausible but wrong line
- Body: "Plausible and correct feel identical to the model."

**S3 · Where it's worst**
- Body: New library versions, internal APIs, niche packages. Anything the model saw little of in training.
- Visual: 3 warning chips: `NEW VERSION` · `INTERNAL` · `NICHE`

**S4 · Fix 1: Ground it in real docs**
- Body: Give it the actual reference: the installed source, the docs page, your internal API file.
- Proof (*example* prompt): `Before using the SDK, read node_modules/<pkg>/README and the type definitions. Only use methods that exist there.`
- DO THIS TODAY: Point it at the type definitions, not your memory.

**S5 · Fix 2: Make reality check it**
- Body: Typecheck, run and test. Hallucinated methods fail fast when you actually execute.
- Proof: `pnpm typecheck && pnpm test -- --run` (*example*)
- Without it: "It compiled in the chat. Not in the terminal."

**S6 · Bonus: connect docs via MCP**
- Body: A docs MCP server lets the agent look things up itself (see Part [5]).

**S7 · Cheat sheet**
| Symptom | Cause | Fix |
|---|---|---|
| Method doesn't exist | Pattern-matching | Point it at the types/source |
| Old syntax | Training on older versions | Tell it the version + docs |
| Made-up internal API | Never seen your code | Have it read the file first |
| "Works" in chat only | Never executed | Typecheck + run |

**S8 · Closer:** SAVE THIS · "Plausible isn't correct. Make it read, then make it run." · `Anatomy · Part [6]`

## Caption
Your AI agent just called a function that doesn't exist. It's not lying. It's pattern-matching.

Models learn what code usually looks like, not what your specific library version contains. It's worst with new versions, internal APIs and niche packages.

2 fixes:
1. Ground it: make it read the real docs, types or source first
2. Reality-check it: typecheck + run + test. Fake methods fail fast.

Plausible isn't correct. Make it read, then make it run.

Save this.

## Hashtags
#aiagents #llm #hallucination #claudecode #aicoding

## First comment
Tip: put "Before using any external library, read its installed type definitions" in your CLAUDE.md rules. Template: comment AGENT.

## Stories (same day)
1. Question box: "Worst hallucinated API your agent ever invented?" (repost the best ones)
