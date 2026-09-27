# Evals: How You Know Your Agent Actually Got Better

**Date:** Thu Nov 26, 2026 · **Format:** Carousel (8 slides, dark teal) · **Series:** Anatomy of an Agent · Part [11] · **CTA:** Save · **Post:** post[N]
**Needs:** none

## Slides
**S1 · Cover.** Kicker: `ANATOMY OF AN AGENT · PART [11]`
- Hook: "You changed your prompt and it 'feels better'. / **Feels isn't a metric.**"
- Illustration: a scoreboard: `v1: 6/10 → v2: 8/10` on the same test set (*illustrative*)
- Bottom: "Evals are just tests" / **"for the fuzzy parts."**

**S2 · What an eval is**
- Headline: "A fixed set of tasks, a way to score each, run before and after a change."
- Visual: TASKS → AGENT → SCORE, repeated for v1 and v2

**S3 · Why vibes fail**
- Body: "You remember the 2 great answers and forget the 3 regressions."
- Visual: two green ticks, big; three red crosses, small and faded

**S4 · Step 1: Collect 10–20 real tasks**
- Body: From your actual usage: the ones it got wrong especially.
- DO THIS TODAY: start a file. Every time the agent fails, add the task.

**S5 · Step 2: Decide how to score**
- Code checks (tests pass, output matches) where you can
- A rubric (1–5 on specific criteria) where you can't
- Another model as grader: useful, but spot-check it

**S6 · Step 3: Run before and after every change**
- New prompt, new model, new CLAUDE.md → re-run → compare.
- Without it: "I 'improved' the prompt and broke 3 things I didn't check."

**S7 · Cheat sheet**
| Part | Start with |
|---|---|
| Tasks | 10–20 real ones, include failures |
| Scoring | Tests > rubric > model grader |
| When | Every prompt/model/config change |
| Where | A folder in the repo |

**S8 · Closer:** SAVE THIS · "Start the failure file today. It's your future eval set." · `Anatomy · Part [11] · Final part`

## Caption
You changed your agent's prompt and it "feels better". Feels isn't a metric.

An eval is a fixed set of tasks + a way to score each, run before and after every change.

1. Collect 10–20 real tasks, especially ones it failed
2. Score with tests where you can, a rubric where you can't
3. Re-run on every prompt, model or config change

Vibes remember the wins and forget the regressions.

Save this, and start your "failure file" today.

## Hashtags
#evals #llm #aiagents #machinelearning #agenticai

## First comment
Further reading: Anthropic's docs on building evals / success criteria (verify on the day). Happy Thanksgiving to everyone celebrating 🦃

## Stories (same day)
1. Poll: "Do you test your prompts?" Evals / Vibes / What are evals
