# Contributing to siafuDB

Thank you for helping. These rules apply to every repository under
[`siafuDB`](https://github.com/siafuDB) unless a repository's own
`CONTRIBUTING.md` says otherwise. The org-wide standard they follow is
[`nyuchi/.github` CONTRIBUTING.md](https://github.com/nyuchi/.github/blob/main/CONTRIBUTING.md).

Related files:

- [`SECURITY.md`](./SECURITY.md): report vulnerabilities privately, never in an issue.
- [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md): how we treat each other.
- [`AGENTS.md`](./AGENTS.md): rules for AI-assisted contributions.

## Workflow

1. Open or find an issue describing the change. Large work gets an issue first.
2. Branch from `main` as `<type>/<short-kebab-description>`. There is one
   long-lived branch, `main`; every pull request targets it.
3. Make the change with its tests and documentation. Run the repository's
   own lint, type check and test commands (see its README or `AGENTS.md`).
4. Open a pull request. Its title follows
   [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
   (`feat`, `fix`, `perf`, `refactor`, `docs`, `test`, `build`, `ci`,
   `chore`, `revert`, `style`), with no trailing period. Link the issue
   with `Closes #n` or `Refs #n`.
5. Keep CI green and resolve review threads. Maintainers merge through the
   merge queue.

## Standards

- **No secrets.** Never commit keys, tokens, `.env` files or personal data.
- **Pin GitHub Actions** to a full 40-character commit SHA.
- **Add or update tests** for behaviour you change, and update the docs.
- **Justify new runtime dependencies** in the pull request: name, version,
  licence and why.
- **Sign your commits** and add a `Signed-off-by:` trailer (`git commit -s`)
  where the repository requires it.
- **Breaking changes** are marked with `!` in the title and a
  `BREAKING CHANGE:` footer. A major version is never cut without the
  owners' approval.

## Questions

Use the repository's issues for questions about a project, and see
[`SUPPORT.md`](https://github.com/nyuchi/.github/blob/main/SUPPORT.md) for
other help.
