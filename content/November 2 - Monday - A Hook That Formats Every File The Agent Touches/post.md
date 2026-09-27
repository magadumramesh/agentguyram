# A Hook That Formats Every File The Agent Touches

**Date:** Mon Nov 2, 2026 · **Format:** Reel (split-screen, ~30s) · **Series:** Watch It Work · **CTA:** Comment AGENT · **Post:** post[N]
**Needs:** 🎥 face · 🖥️ screen

## Hook
- **On screen:** "I stopped asking my agent to format code."
- **Spoken:** "I've asked my AI agent to run the formatter maybe a hundred times. It forgets. So I stopped asking."

## Script
| # | 🎥 You say | Top panel |
|---|---|---|
| 1 | I've asked my AI agent to run the formatter maybe a hundred times. It forgets. So I stopped asking. | Chat bubbles "please run prettier" ×5 |
| 2 | Instructions are suggestions. The agent follows them *most* of the time. | `MOST` underlined |
| 3 | Hooks are different. A hook is a command that runs automatically, every time, at a set moment. | Lightning icon + `ALWAYS` |
| 4 | This one says: after any file edit, run the formatter on that file. | Code card: the PostToolUse hook from settings.example.json |
| 5 | Watch: the agent edits, and the file's formatted before it even moves on. | 🖥️ edit → file instantly formatted |
| 6 | No reminder. No "oops, forgot". It just happens. | ✓ |
| 7 | If you've said it twice, write a rule. If it forgets the rule, write a hook. | Closer |
| 8 | The config's in my Starter Kit. Comment AGENT. | AGENT pill |

## 🎥 What you need to do
- [ ] Add the hook from `starter-kit/settings.example.json` to your repo's `.claude/settings.json` (swap in your formatter)
- [ ] 🖥️ **SCREEN RECORD** the agent editing a file and the formatter kicking in (split view: agent + file)
- [ ] 🎥 **RECORD** lines 1–8
- [ ] Fact-check the hook schema against the current Claude Code hooks docs

## Cover
- Hook: "I stopped asking / my agent to / **format code.**"
- Illustration: a lightning bolt between "Edit file" and "Formatter runs"
- Bottom: "Instructions are suggestions." / **"Hooks always run."**

## Caption
I've asked my AI agent to run the formatter maybe 100 times. It forgets. So I stopped asking.

Instructions are suggestions: the agent follows them most of the time.

Hooks always run. A hook is a command that fires automatically at a set moment, like after every file edit.

Mine: after any edit, format that file. No reminders, no "oops".

Said it twice? Write a rule. It forgets the rule? Write a hook.

Comment AGENT for the config.

## Hashtags
#claudecode #automation #aiagents #agenticcoding #developertools

## First comment
Source: Claude Code docs → Hooks (PostToolUse event, matcher on Edit|Write). The config is in the Starter Kit's settings.example.json. Adjust the command for your formatter.

## Stories (same day)
1. Poll: "What does your agent keep forgetting?" Formatting / Tests / Lint / Everything 😅
