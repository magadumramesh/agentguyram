# When One Agent Isn't Enough

**Date:** Thu Nov 12, 2026 · **Format:** Carousel (8 slides, dark teal) · **Series:** Anatomy of an Agent · Part [9] · **CTA:** Save · **Post:** post[N]
**Needs:** none (fact-check only)

## Slides
**S1 · Cover.** Kicker: `ANATOMY OF AN AGENT · PART [9]`
- Hook: "Multi-agent systems sound cool. / **Most of the time you need exactly one agent.**"
- Illustration: one agent node vs a tangled graph of five nodes
- Bottom: "Here's when more is better" / **"and when it's just more."**

**S2 · The default**
- Headline: "Start with one agent + good tools. Add agents only when you hit a specific wall."
- Body: "Every extra agent adds handoffs, and every handoff loses detail."

**S3 · Pattern 1: Orchestrator → workers**
- Body: A lead agent splits the task and sends parts to workers, then combines the results.
- Good for: research across many sources; big parallel searches.
- Visual: 1 → 3 → 1

**S4 · Pattern 2: Maker → checker**
- Body: One agent does, another critiques. A fresh context catches what the maker can't.
- Good for: code review, fact-checking, writing.

**S5 · Pattern 3: Specialists**
- Body: Different agents with different tools and permissions (read-only researcher, write-enabled builder).
- Good for: safety, keeping dangerous tools in one small box.

**S6 · The walls that justify it**
- Context fills up → split the work
- Needs a fresh eye → add a checker
- Needs different permissions → specialists
- Otherwise → one agent

**S7 · Cheat sheet**
| Pattern | Shape | Use when |
|---|---|---|
| Single agent | 1 | Almost always, to start |
| Orchestrator–workers | 1→N→1 | Big, parallel, separable |
| Maker–checker | 1⇄1 | Quality matters |
| Specialists | tools split | Permission boundaries |

**S8 · Closer:** SAVE THIS · "One agent until it hurts." · `Anatomy · Part [9]`

## Caption
Multi-agent systems sound cool. Most of the time you need exactly one agent with good tools.

Add more only when you hit a specific wall:
→ context filling up? Orchestrator → workers
→ need a fresh eye? Maker → checker
→ need different permissions? Specialists

Every extra agent is another handoff, and every handoff loses detail.

One agent until it hurts. Save this.

## Hashtags
#multiagent #aiagents #agenticai #aiarchitecture #claudecode

## First comment
Further reading: Anthropic's posts on building effective agents and on their multi-agent research system (verify titles/links on the day). Subagents in Claude Code are an easy way to try maker→checker: my reviewer subagent is in the Starter Kit (comment AGENT).

## Stories (same day)
1. Poll: "How many agents in your setup?" 1 / 2–3 / 4+ / "yes"
