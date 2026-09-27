# The 5-line task spec

Paste this, fill it in, and hand it to your agent. It takes 2 minutes and saves an hour of rework.

```
GOAL:        [What should be true when this is done, in one sentence a user would understand.]
CONTEXT:     [Files, pages or functions involved. Links to the related issue/design.]
DONE WHEN:   [2–4 checkable acceptance criteria. "Returns 404 for unknown id", not "works well".]
NOT DOING:   [What's out of scope. Stop the agent from "helpfully" rewriting things.]
CHECK BY:    [The exact command or steps to prove it works.]
```

## Example (illustrative)

```
GOAL:        Logged-in users can reset their password from the settings page.
CONTEXT:     src/app/settings/page.tsx, src/lib/auth.ts, existing email helper in src/lib/email.ts
DONE WHEN:   - "Reset password" button sends a reset email via the existing helper
             - Reset link expires after 30 minutes
             - Using an expired link shows "Link expired" and a resend button
NOT DOING:   No changes to sign-up or login. No new email provider. No UI redesign.
CHECK BY:    pnpm test -- --run auth ; then manually: settings -> reset -> check the dev inbox
```

Why it works: it's the same thing a good PM writes for a human engineer. Agents fail in the same places people do: vague goals, no scope and no definition of done.
