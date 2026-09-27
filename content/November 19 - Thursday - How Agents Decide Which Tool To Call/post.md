# How Agents Decide Which Tool To Call

**Date:** Thu Nov 19, 2026 · **Format:** Carousel (8 slides, dark teal) · **Series:** Anatomy of an Agent · Part [10] · **CTA:** Save · **Post:** post[N]
**Needs:** none (fact-check only)

## Slides
**S1 · Cover.** Kicker: `ANATOMY OF AN AGENT · PART [10]`
- Hook: "Your agent picks tools by reading their descriptions. / **Bad description, wrong tool.**"
- Illustration: 3 tool cards, the model's "eye" scanning their descriptions; one highlighted
- Bottom: "Tool descriptions are prompts." / **"Write them like it."**

**S2 · How it works**
- Headline: "Every available tool comes with a name, a description and an input schema. The model sees all of them."
- Visual: a tool card: `name` / `description` / `inputs`
- Body: "It chooses based on those words, not on what the code actually does."

**S3 · Failure 1: Vague description**
- Without a fix (*illustrative*): `search: "Searches stuff."` → it searches the web when you meant your database.
- Fix: `search_orders: "Search customer orders by email or order ID. Use for order-status questions."`

**S4 · Failure 2: Overlapping tools**
- Body: Two tools that sound alike → coin flip.
- Fix: say when to use each, *and when not to*.

**S5 · Failure 3: Too many tools**
- Body: 60 tools means 60 descriptions to weigh, and more chances to pick wrong.
- Fix: only connect what the task needs; use specialist subagents for the rest.

**S6 · Failure 4: Unclear inputs**
- Fix: name the parameters clearly, give formats and examples (`date: YYYY-MM-DD`).

**S7 · Cheat sheet**
| Write | Example |
|---|---|
| What it does | "Search orders by email or ID" |
| When to use it | "For order-status questions" |
| When NOT to | "Not for refunds; use refund_order" |
| Input formats | "email: string, e.g. a@b.com" |

**S8 · Closer:** SAVE THIS · "Building an MCP server? Your descriptions are your UX." · `Anatomy · Part [10]`

## Caption
Your AI agent picks tools by reading their descriptions, not their code.

Bad description, wrong tool.

The 4 failures:
1. Vague ("Searches stuff.")
2. Overlapping tools that sound alike
3. Too many tools connected at once
4. Unclear inputs

Fix: say what it does, when to use it, when NOT to, and the input formats.

If you build MCP servers or agent tools, the descriptions are your UX. Save this.

## Hashtags
#mcp #aiagents #tooluse #llm #agenticai

## First comment
Further reading: Anthropic's guidance on writing tools for agents, and the MCP docs on tool definitions (verify links on the day).

## Stories (same day)
1. Quiz: "What does the model use to choose a tool?" The code / The description ✅ / Random
