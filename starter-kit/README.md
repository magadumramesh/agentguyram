# The Agent Starter Kit (free)

The files I use to make coding agents (Claude Code, Cursor, Codex) actually useful on real projects. Copy them into your repo and edit to match your project.

This is what you get when you comment **AGENT** on an @agentguyram post.

| File | What it does | Post that explains it |
|---|---|---|
| [`CLAUDE.md.template`](CLAUDE.md.template) | Project memory your agent reads every session | ACE: "Stop re-explaining your project" |
| [`task-spec.md`](task-spec.md) | The 5-line spec that stops agent rework | ACE: "The 5-line task spec" |
| [`plan-first-prompts.md`](plan-first-prompts.md) | Copy-paste prompts: plan, verify, review | Cheat Sheet Sundays |
| [`verification-checklist.md`](verification-checklist.md) | What to check before you merge agent code | "Verification checklist before you merge" |
| [`.claude/agents/`](.claude/agents/) | 3 subagents: reviewer, test-writer, researcher | "Subagent recipes" |
| [`.claude/skills/release-notes/`](.claude/skills/release-notes/SKILL.md) | An example Skill: release notes from git history | "Your first Skill in 10 minutes" |
| [`settings.example.json`](settings.example.json) | A safe permissions allowlist + a format-on-edit hook | "Hooks" and "Permissions" |

## How to use
1. Copy `CLAUDE.md.template` to your repo root as `CLAUDE.md` and fill in the brackets.
2. Copy the `.claude/` folder into your repo root.
3. Merge `settings.example.json` into `.claude/settings.json`. Change the commands to your stack's.
4. Keep `task-spec.md` and `plan-first-prompts.md` open while you work.

> These are starting points, not gospel. Tools change fast, so check each feature against the current docs for your agent before relying on it.

Follow [@agentguyram](https://instagram.com/agentguyram) for a new upgrade every day.
