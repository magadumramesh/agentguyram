---
name: release-notes
description: Write user-facing release notes from recent git history. Use when asked for release notes, a changelog, or "what shipped this week".
---

# Release notes

1. Find the range: since the last tag (`git describe --tags --abbrev=0`), or the last 7 days if there are no tags (`git log --since="7 days ago"`).
2. Read `git log --oneline` for that range. For anything unclear, read the diff (`git show <sha> --stat`).
3. Group the changes into **New**, **Improved** and **Fixed**. Drop internal-only changes (refactors, CI, deps) unless users would notice them.
4. Write each item as one line a customer would understand: what they can do now, not what the code does.
5. Output markdown. Keep it under 15 lines. End with the date range covered.

Never invent features that aren't in the commits. If a commit message is too vague to describe, list it under "Needs a human" at the bottom.
