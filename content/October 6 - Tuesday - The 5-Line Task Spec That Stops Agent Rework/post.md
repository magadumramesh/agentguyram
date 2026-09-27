# The 5-Line Task Spec That Stops Agent Rework

**Date:** Tue Oct 6, 2026 · **Format:** Carousel (9 slides) · **Series:** ACE · Day [16] · **CTA:** Save · **Post:** post[N]
**Needs:** none

## Slides
**S1 · Cover.** Kicker: `ACE AGENTIC CODING · DAY [16]`
- Hook: "Your agent keeps redoing work because your task is 1 line. / **Make it 5.**"
- Illustration: before/after cards. Before: `"add password reset"`. After: 5 labelled lines, GOAL · CONTEXT · DONE WHEN · NOT DOING · CHECK BY
- Bottom: "2 minutes to write." / **"An hour of rework saved."**

**S2 · Why it matters**
- Headline: "Agents fail where new hires fail: vague goals, no scope, no finish line."
- Visual: three broken-link icons labelled vague · unscoped · no "done"
- Body: "The fix isn't a smarter model. It's a better ticket."

**S3 · Line 1: GOAL**
- Body: What's true when it's done, in words a user would understand.
- Without it: "It built the backend. I wanted the button."
- Proof (*example*): `GOAL: Logged-in users can reset their password from Settings.`
- DO THIS TODAY: Write it without any technical words.

**S4 · Line 2: CONTEXT**
- Body: The files, pages or helpers involved.
- Without it: "It wrote a new email sender. We had one."
- Proof (*example*): `CONTEXT: settings/page.tsx, lib/auth.ts, existing lib/email.ts`

**S5 · Line 3: DONE WHEN**
- Body: 2–4 checkable acceptance criteria.
- Without it: "It said 'done'. Done how?"
- Proof (*example*): `- Link expires after 30 min` / `- Expired link shows "resend"`

**S6 · Line 4: NOT DOING**
- Body: What's out of scope. This is the line people skip, and the one that matters most.
- Without it: "I asked for reset. It redesigned the login page."
- Proof (*example*): `NOT DOING: no sign-up changes, no new email provider, no UI redesign`

**S7 · Line 5: CHECK BY**
- Body: The exact command or click-path that proves it works.
- Without it: "'Tests pass.' Which tests? It didn't run any."
- Proof (*example*): `CHECK BY: pnpm test -- --run auth, then Settings → Reset → dev inbox`

**S8 · Cheat sheet:** the 5-line template as one card
```
GOAL:      [user-visible outcome]
CONTEXT:   [files / helpers]
DONE WHEN: [2–4 checks]
NOT DOING: [out of scope]
CHECK BY:  [command / steps]
```

**S9 · Closer:** SAVE THIS · "Use it on your very next task." · `ACE · Day [16] · Next: making it prove its work`

## Caption
Your AI agent keeps redoing work because your task is one line long. Make it five:

GOAL: the user-visible outcome
CONTEXT: the files and helpers involved
DONE WHEN: 2–4 checkable criteria
NOT DOING: what's out of scope (the line everyone skips)
CHECK BY: the command that proves it

It takes 2 minutes and saves an hour of back-and-forth. It's the same thing a good PM writes for a human engineer.

Save this and use it on your next task.

## Hashtags
#claudecode #agenticcoding #aicoding #productmanagement #aiagents

## First comment
The template is in the free Agent Starter Kit as a file (task-spec.md). Comment AGENT and I'll DM it.

## Stories (same day)
1. Slide 8 + "Screenshot this 📸"
2. Poll: "Which line do you skip most?" Goal / Context / Done when / Not doing / Check by
