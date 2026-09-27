# Before you merge agent code

## The agent did
- [ ] Ran the tests and **showed the output** (not "tests should pass")
- [ ] Ran lint + typecheck
- [ ] Told you what it didn't do or wasn't sure about

## You check
- [ ] **Read the diff, not the chat.** The chat is the agent's story; the diff is what actually changed.
- [ ] No files changed that the task didn't need
- [ ] No new dependencies you didn't approve
- [ ] No tests deleted, skipped or weakened to go green
- [ ] No secrets, keys or `.env` values in the diff
- [ ] Error paths handled (empty input, not found, network failure)
- [ ] You ran it yourself once: clicked the button, hit the endpoint, ran the CLI

## Red flags: stop and look closer
- "I've simplified the test to make it pass"
- Mocks that replace the thing being tested
- A big diff for a small ask
- `// TODO` where the hard part should be
- Confident claims about an API you've never seen in this codebase
