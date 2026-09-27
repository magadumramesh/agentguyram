# Skills vs Prompts vs MCP: Which Do You Actually Need?

**Date:** Thu Oct 29, 2026 · **Format:** Carousel (8 slides, dark teal) · **Series:** Anatomy of an Agent · Part [7] · **CTA:** Save · **Post:** post[N]
**Needs:** none (fact-check only)

## Slides
**S1 · Cover.** Kicker: `ANATOMY OF AN AGENT · PART [7]`
- Hook: "CLAUDE.md, Skills, slash commands, subagents, MCP. / **Which one do you actually need?**"
- Illustration: a decision tree with 5 leaves
- Bottom: "Five features," / **"one question each."**

**S2 · The one question**
- Headline: "What are you trying to give the agent?"
- Visual: 5 answer chips: RULES · KNOW-HOW · A SHORTCUT · A HELPER · ACCESS

**S3 · RULES → CLAUDE.md**
- Body: Always-true facts and rules. Loaded every session.
- Example: "Use pnpm. Never push to main."

**S4 · KNOW-HOW → Skill**
- Body: A repeatable procedure, loaded only when relevant.
- Example: "How we write release notes."

**S5 · A SHORTCUT → slash command**
- Body: A prompt *you* trigger on purpose.
- Example: `/review`

**S6 · A HELPER → subagent**
- Body: A separate worker with its own context and tools.
- Example: A read-only researcher.

**S7 · ACCESS → MCP**
- Body: Connects the agent to a system it can't reach otherwise.
- Example: Your issue tracker or database.

**S8 · Cheat sheet + closer**
| You want to give it… | Use | Loaded |
|---|---|---|
| Rules | CLAUDE.md | Every session |
| Know-how | Skill | When relevant |
| A shortcut | Slash command | When you type it |
| A helper | Subagent | When delegated |
| Access | MCP server | Tools always available |
- SAVE THIS · `Anatomy · Part [7]`

## Caption
CLAUDE.md, Skills, slash commands, subagents, MCP. Which one do you actually need?

Ask: what am I giving the agent?

📜 Rules → CLAUDE.md (every session)
🧠 Know-how → a Skill (loaded when relevant)
⌨️ A shortcut → a slash command (you trigger it)
🤝 A helper → a subagent (own context, own tools)
🔌 Access → MCP (connects outside systems)

Save this. It's the map I wish I'd had.

## Hashtags
#claudecode #mcp #agentskills #aiagents #agenticcoding

## First comment
Sources: Claude Code docs → Memory, Skills, Slash commands, Subagents, MCP. Features overlap and evolve, so check the current docs. Examples of each are in the Starter Kit (comment AGENT).

## Stories (same day)
1. Quiz: "Where should 'always use pnpm' go?" CLAUDE.md ✅ / Skill / MCP
