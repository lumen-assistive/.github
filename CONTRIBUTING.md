# Contributing to Lumen

Thank you for considering a contribution. This file describes the
workflow shared by every repository in the `lumen-assistive`
organization; check each repository's own `CONTRIBUTING.md` for
stack-specific setup (Flutter, Python, Astro, and so on).

## Before you start

- Search existing issues before opening a new one.
- For a change larger than a small fix, open an issue first to discuss
  the approach.
- Issues labeled `good first issue` are a good entry point if you are
  new to the project.

## Workflow

1. Fork the repository and create a branch from `main` named
   `type/short-description` (for example `fix/ocr-crash-on-empty-frame`).
2. Install the repository's commit message hook before committing:
   ```
   git config core.hooksPath .githooks
   ```
3. Make your change, including tests. Run the repository's lint, format,
   analyze and test commands locally before opening a pull request; see
   that repository's README for the exact commands.
4. Write commits in English, following
   [Conventional Commits](https://www.conventionalcommits.org/), as
   small and atomic units.
5. Open a pull request against `main` using the pull request template.
   Describe what changed and why, and link the issue it closes if any.

## Code standards

- All code, identifiers, comments, commit messages, and documentation
  are written in English. Application user interface strings are
  localized separately, with Italian as the primary locale.
- Comments explain intent, constraints and non-obvious decisions, not
  what the code already says. Do not leave commented-out code or
  `TODO`/`FIXME` markers; open an issue instead.
- Public APIs require complete documentation comments in the language's
  idiomatic doc comment format.
- No emoji in code, commits, documentation, or user interface text.
- Do not add a dependency, tool, model, or library that is not already
  referenced in the target repository's documentation without first
  discussing it in an issue.

## Accessibility and privacy

Lumen's purpose is accessibility; treat it as a hard requirement, not a
follow-up task. Any user-facing change must keep screen reader labels,
sufficient contrast, adequate touch target size and voice reachability
intact. Any change touching sensors, microphone, camera, location, or
model downloads must preserve on-device processing by default and
explicit, revocable user consent for anything that is not.

## Reporting a security issue

Do not open a public issue for a security vulnerability. See
`SECURITY.md` in the affected repository for the private reporting
process.
