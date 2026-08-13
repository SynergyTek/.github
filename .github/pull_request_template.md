<!--
Title format:  <type>(<scope>): <what changed>
  fix(auth): reject expired refresh tokens instead of returning 500
  feat(api): add pagination to the search endpoint
  docs(readme): document the local setup steps
Types: feat fix docs ci chore refactor test perf build revert
Do not title a PR after its branch ("Development", "changes", "fixes").
-->

## What changed

<!-- One or two sentences in plain English. What does this do that the code did not do before? -->

## Why

Closes #

<!-- Every PR should close or reference an issue. If there genuinely isn't one,
     say why here in a sentence. -->

## How to verify

<!-- The steps a reviewer follows to confirm this works. Be specific:
     which screen, which endpoint, what they should see. -->

1.
2.

## Risk

- [ ] No schema or migration changes
- [ ] No config or environment variable changes
- [ ] No breaking API changes
- [ ] No new dependencies

<!-- Tick what applies. Anything left unticked, explain below. -->

## Checks

- [ ] Builds and runs locally
- [ ] Self-reviewed the diff
- [ ] No secrets, keys, connection strings or real hostnames in the diff
- [ ] No debug logging left behind (`console.log`, `Console.WriteLine`)
