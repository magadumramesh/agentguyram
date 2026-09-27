# Watch The Agent Plan Before It Touches Code

**Date:** Mon Oct 5, 2026 · **Format:** Reel (split-screen, ~35s) · **Series:** Watch It Work · **CTA:** Comment AGENT · **Post:** post[N]
**Needs:** 🎥 face · 🖥️ screen · [RAM INPUT]

> The first AGENT CTA. Make sure the DM automation is live (see `starter-kit-dm-setup.md`), or switch the CTA to Save.

## Hook
- **On screen:** "Stop letting your agent code first"
- **Spoken:** "The fastest way to get good code from an AI agent? Don't let it write any. Yet."

## Script
| # | 🎥 You say | Top panel |
|---|---|---|
| 1 | The fastest way to get good code from an AI agent? Don't let it write any. Yet. | `CODE: 0 lines` counter |
| 2 | This is plan mode. In Claude Code it's Shift+Tab. | 🖥️ pressing Shift+Tab, mode label changes |
| 3 | The agent can read my codebase, but it can't edit anything. | `READ ✓ · EDIT ✗` chips |
| 4 | So I give it the task: [RAM INPUT: a real feature from your SaaS]. | 🖥️ typing the task |
| 5 | And it comes back with a plan. Which files, what changes, in what order. | 🖥️ the plan appears (sped up), then key lines highlighted |
| 6 | But look at step [RAM INPUT: n]. It wanted to [RAM INPUT: the thing you'd have rejected]. | Circle that step in orange |
| 7 | I caught that in 10 seconds of reading. In code, that's 20 minutes of undoing. | `10s` vs `20 min` |
| 8 | Therefore: plan first, fix the plan, then say go. | 3 steps light up |
| 9 | My plan-first prompts are in my free Agent Starter Kit. Comment AGENT and I'll send it. | `COMMENT "AGENT"` pill pulses |

## 🎥 What you need to do
- [ ] 🖥️ **SCREEN RECORD** a real plan-mode session: Shift+Tab → task → the plan → you editing/rejecting one step → "go"
- [ ] 🎥 **RECORD** lines 1–9
- [ ] [RAM INPUT] Beats 4 and 6: the real task and the real step you pushed back on
- [ ] Fact-check: the plan-mode shortcut in the current Claude Code docs

## Cover
- Hook: "Stop letting your / AI agent / **code first.**"
- Illustration: a plan card with 4 numbered steps; step 3 is struck through in orange with a note "no, reuse lib/auth"
- Bottom: "10 seconds reading a plan" / **"saves 20 minutes undoing code."**

## Caption
The fastest way to get good code from an AI agent: don't let it write any. Yet.

Plan mode in Claude Code (Shift+Tab) lets the agent read your whole codebase but not edit it. You get a plan first: which files, what changes, what order.

Then you fix the plan. That's 10 seconds of reading instead of 20 minutes of undoing code.

Plan → fix the plan → go.

Comment AGENT and I'll DM you my free Agent Starter Kit with the plan-first prompts I use.

## Hashtags
#claudecode #agenticcoding #aicoding #aiagents #softwaredevelopment

## First comment
Source: Claude Code docs → plan mode. No plan mode in your tool? Use prompt #1 from the kit: "Read the relevant files, give me a numbered plan, don't edit until I say go."

## Stories (same day)
1. "The kit is live 📩 Comment AGENT on any post"
2. Screenshot of a real plan with your edit circled
