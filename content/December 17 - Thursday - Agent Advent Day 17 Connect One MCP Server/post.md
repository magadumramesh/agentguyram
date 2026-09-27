# Agent Advent Day 17: Connect One MCP Server

**Date:** Thu Dec 17, 2026 · **Format:** Carousel (6 slides) · **Series:** Agent Advent · Day 17/24 · **CTA:** Save · **Post:** post[N]
**Needs:** fact-check the add-server command + pick real, current example servers

## Slides
**S1 · Cover.** Kicker: `AGENT ADVENT · DAY 17/24`
- Hook: "You alt-tab to the same tool 30 times a day. / **Plug it into your agent instead.**"
- Illustration: an agent with one new plug connected; 3 unplugged plugs waiting
- Bottom: "Just one." / **"The one you alt-tab to most."**

**S2 · Pick your one**
- Issue tracker (read tickets, don't paste them) · docs (look up real APIs) · database (**read-only**) · browser (test your UI)

**S3 · How** (code card, *example*; check the docs)
```
claude mcp add <name> -- <command that starts the server>
```
- Body: "Then ask the agent what tools it now has."

**S4 · The safety rule**
- Headline: "Start read-only."
- Body: "A database connection should be a read replica or a read-only user. Only give write access once you trust it."

**S5 · The test**
- Body: "Ask something that needs the new tool: 'Summarise ticket #123 and find the code it refers to.'"

**S6 · Closer:** SAVE THIS · "Door 17 ✅" · grid

## Caption
🎄 Agent Advent, Day 17/24: connect ONE MCP server.

The one you alt-tab to most: your issue tracker, docs, a database (read-only!), or a browser.

claude mcp add <name> -- <server command>

Then test it: "Summarise ticket #123 and find the code it refers to."

The rule: start read-only. Give write access once you trust it.

Save this.

## Hashtags
#mcp #claudecode #agentadvent #aiagents #adventcalendar

## First comment
Directory of servers: modelcontextprotocol.io (and your tool's docs). [Optional RAM INPUT: "I connected X, and it changed Y."] Refresher on what MCP is: my Oct 15 post.

## Stories (same day)
1. Door 17 ✅ · poll: "Which would you connect?" Tickets / Docs / DB / Browser
