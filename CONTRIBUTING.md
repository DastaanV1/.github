# Contributing to Dastaan

Follow the contribution guide in the repository you are changing. Write a Conventional Commit message and link the relevant issue or delivery batch in the pull request. Explain the change and report the checks you ran.

## Branch naming

Create a short-lived branch from `main`. Name it `<prefix>/<branchname>` and choose a prefix from the table below. After the slash, use one or more groups of lowercase letters or digits separated by single hyphens. An issue number is optional, as in `feat/123-offline-drafts`.

| Prefix | Use |
| --- | --- |
| `feat/` | New features or capabilities |
| `bug/` or `fix/` | Bug fixes |
| `error/` | Changes to error handling, reporting or recovery |
| `hotfix/` | Urgent fixes for production issues |
| `chore/` | Routine repository or tooling maintenance |
| `docs/` | Documentation |
| `refactor/` | Internal restructuring |
| `perf/` | Performance improvements |
| `test/` | Tests and fixtures |
| `build/` | Build configuration and packaging |
| `ci/` | CI workflows and checks |
| `deps/` | Dependency updates |
| `style/` | Formatting and style cleanup |
| `security/` | Security fixes or hardening |
| `release/` | Release preparation |

## Organization repository

Keep the organization profile, templates and reusable workflows in this repository. Treat every committed file as public. Keep project credentials, internal links and private operational details in the appropriate private repository or secret store.

Run `git diff --check` and verify Markdown links before opening a pull request. For workflow changes, pin third-party actions to full commit SHAs, review job permissions and validate callers affected by the change.

Report security issues through GitHub private vulnerability reporting where enabled.
