# Hooks: Make Your Agent Follow Rules It Keeps Forgetting

**Date:** Tue Nov 3, 2026 · **Format:** Carousel (9 slides) · **Series:** ACE · Day [20] · **CTA:** Save · **Post:** post[N]
**Needs:** none (fact-check only)

## Slides
**S1 · Cover.** Kicker: `ACE AGENTIC CODING · DAY [20]`
- Hook: "Your agent follows CLAUDE.md *most* of the time. / **Hooks make it every time.**"
- Illustration: two lanes. "Instruction" → 80% dotted arrow. "Hook" → solid arrow, 100%. (Illustrative, no real numbers: label it "illustrative")
- Bottom: "Rules are requests." / **"Hooks are guarantees."**

**S2 · What a hook is**
- Headline: "A shell command that runs automatically at a specific moment in the agent's loop."
- Visual: the agent loop from Part [3], with hook points marked: before a tool · after a tool · when it stops
- Body: "The model doesn't decide whether to run it. The harness does."

**S3 · Moment 1: before a tool runs (PreToolUse)**
- Body: Check, and optionally block, what the agent's about to do.
- Use: block edits to protected folders.
- Without it: "It edited generated files. Again."

**S4 · Moment 2: after a tool runs (PostToolUse)**
- Body: React to what just happened.
- Use: format or lint every edited file.
- Proof (*example*): `"matcher": "Edit|Write"` → `prettier --write <file>`

**S5 · Moment 3: when it finishes (Stop)**
- Body: Run a final check when the agent says it's done.
- Use: run the fast test suite.
- Without it: "It stopped. The build was broken."

**S6 · Moment 4: notifications**
- Body: Get pinged when it needs you, so you're not watching the terminal.
- Use: a desktop notification.

**S7 · Where it lives**
- Proof: `.claude/settings.json` → `"hooks": { "PostToolUse": [ … ] }`
- Body: "It's in the repo, so the whole team gets the same guarantees."

**S8 · Cheat sheet**
| Moment | Event | Classic use |
|---|---|---|
| Before a tool | PreToolUse | Block protected paths |
| After a tool | PostToolUse | Format / lint |
| Done | Stop | Run fast tests |
| Needs you | Notification | Desktop ping |

**S9 · Closer:** SAVE THIS · "Start with format-on-edit. It pays off on day one." · `ACE · Day [20]`

## Caption
Your AI agent follows CLAUDE.md most of the time. Hooks make it happen every time.

A hook is a shell command that runs automatically at a set point in the agent's loop. The model doesn't decide whether to run it, the harness does.

⏮ Before a tool (PreToolUse): block edits to protected folders
⏭ After a tool (PostToolUse): format/lint every edited file
🏁 When it stops (Stop): run the fast test suite
🔔 Notification: ping you when it needs you

Rules are requests. Hooks are guarantees.

Save this.

## Hashtags
#claudecode #automation #agenticcoding #aiagents #devops

## First comment
Source: Claude Code docs → Hooks (events + JSON input format). Event names can change, so check yours. Working example: the Starter Kit's settings.example.json (comment AGENT).

## Stories (same day)
1. Quiz: "Which hook formats files after edits?" PreToolUse / PostToolUse ✅ / Stop
