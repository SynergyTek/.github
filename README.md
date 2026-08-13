# .github

Default issue and pull request templates for the SynergyTek organisation.

Any repository in the org that does not define its own templates inherits these
automatically. A repository can override them by adding its own
`.github/ISSUE_TEMPLATE/` folder or `pull_request_template.md`.

## What is here

```
.github/
├── pull_request_template.md
└── ISSUE_TEMPLATE/
    ├── bug_report.yml       Something behaves incorrectly
    ├── security.yml         A vulnerability in our own code or configuration
    ├── enhancement.yml      New capability or improvement
    └── config.yml           Disables blank issues
```

## Conventions

**Commit and PR titles** follow [Conventional Commits](https://www.conventionalcommits.org):

```
<type>(<scope>): <what changed>
```

Types: `feat` `fix` `docs` `ci` `chore` `refactor` `test` `perf` `build` `revert`

Keep the subject under 72 characters, in the imperative mood, describing what
changed rather than that something changed. Reference the issue the work relates to.

**Issue labels** — one type and one priority per issue:

- Type: `bug` `enhancement` `task` `spike`
- Priority: `p0-critical` `p1-high` `p2-normal` `p3-low`
- Optional: `security` `blocked` `needs-info`

## Note

This repository is public because GitHub requires it for organisation-wide default
templates. Keep its contents generic — no internal hostnames, credentials, customer
names, or details of unfixed security findings.
