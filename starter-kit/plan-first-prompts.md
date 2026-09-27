# Copy-paste prompts

## 1. Plan before code
```
Before you change anything: read the relevant files, then give me a numbered plan.
For each step: which file, what change, and why. List anything you're unsure about.
Don't edit until I say "go".
```

## 2. Ask me first
```
Before planning, ask me up to 5 questions about anything ambiguous in this task.
Only ask questions whose answers would change what you build.
```

## 3. Smallest change
```
What's the smallest change that satisfies the acceptance criteria?
If your plan touches more than [3] files, explain why each one is necessary.
```

## 4. Prove it
```
Run [test command] and paste the actual output. If anything failed, fix it and run again.
Don't tell me it works. Show me.
```

## 5. Self-review
```
Review your own diff as a strict senior engineer would. List:
1) bugs or edge cases, 2) anything you changed that wasn't asked for, 3) anything you're not sure about.
Then fix 1) and 2).
```

## 6. Explain it back
```
Explain how [feature/module] works in this codebase as if I'm a new teammate:
entry points, data flow, and the 3 files I'd need to read first.
```

## 7. Unstick
```
Stop. Summarise what you've tried, what failed and why.
Then propose 2 different approaches and recommend one. Don't write code yet.
```

## 8. Handoff
```
Summarise this session for the next one: what's done, what's left, decisions we made,
and gotchas. Keep it under 15 lines so I can paste it into a fresh session.
```
