# Tools vs MCP: How Agents Plug Into The World

**Date:** Thu Oct 15, 2026 · **Format:** Carousel (8 slides, dark teal) · **Series:** Anatomy of an Agent · Part [5] · **CTA:** Save · **Post:** post[N]
**Needs:** none (fact-check only)

## Slides
**S1 · Cover.** Kicker: `ANATOMY OF AN AGENT · PART [5]`
- Hook: "An agent without tools is just a chatbot. / **MCP is how it gets more of them.**"
- Illustration: an agent core in the centre with plugs radiating out: Files · Terminal · GitHub · Docs · Database · Slack (all generic icons, no logos)
- Bottom: "Tools are the hands." / **"MCP is the socket standard."**

**S2 · Tools, recap**
- Headline: "A tool is a function the model can ask to use."
- Visual: `model → "call read_file(path)" → tool runs → result → model`
- Body: "Name, description, inputs. The model reads the description to decide when to use it." (Links back to Part [3], the loop.)

**S3 · Built-in tools**
- Body: Coding agents ship with the basics: read, edit, search, run commands.
- Visual: 4 keycaps: READ · EDIT · SEARCH · RUN

**S4 · The problem**
- Body: "But your work lives in 20 other places. Issue tracker, docs, database, design files."
- Without a standard: "Every app needs a custom integration for every agent. That's N × M glue code."

**S5 · MCP: Model Context Protocol**
- Headline: "An open standard for connecting agents to tools and data."
- Visual: USB-C analogy. Many devices, one port shape.
- Body: "Build one MCP server for your tool, and any MCP-compatible agent can use it."

**S6 · What it looks like**
- Proof (*example*, check your tool's docs): `claude mcp add <name> -- <command to start the server>`
- Body: "After that, the agent sees the new tools, with descriptions, the same way it sees built-ins."

**S7 · Cheat sheet**
| Term | Plain English |
|---|---|
| Tool | A function the model can call |
| Tool description | How the model decides when to call it |
| MCP server | A program that offers tools to agents |
| MCP client | The agent app that connects to it |

**S8 · Closer:** SAVE THIS · "Rule of thumb: connect the one system you alt-tab to most." · `Anatomy · Part [5] · Next: why agents hallucinate APIs`

## Caption
An AI agent without tools is just a chatbot.

Tools are the hands: functions the model can ask to use (read a file, run a command, search). The model picks one by reading its description.

MCP (Model Context Protocol) is the socket standard. One MCP server for your issue tracker, database or docs, and any MCP-compatible agent can plug into it.

Tools = hands. MCP = the plug shape.

Save this, and connect the one system you alt-tab to most.

## Hashtags
#mcp #modelcontextprotocol #aiagents #claudecode #agenticai

## First comment
Sources: modelcontextprotocol.io (the spec + server list) and Claude Code docs → MCP. Verify the `claude mcp add` syntax for your version.

## Stories (same day)
1. Question box: "Which tool do you wish your agent could plug into?"
