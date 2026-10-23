# .github

This repository holds organization-wide defaults for `lumen-assistive`:

- `profile/README.md` is rendered on the
  [organization page](https://github.com/lumen-assistive).
- `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md`,
  `.github/ISSUE_TEMPLATE/` and `.github/PULL_REQUEST_TEMPLATE.md` are the
  default community health files applied to any repository in the
  organization that does not define its own.
- `.github/workflows/` holds reusable workflows (`workflow_call`) that
  other repositories in the organization invoke for Dart/Flutter and
  Python continuous integration, so CI configuration stays consistent
  and is maintained in one place.
- `.githooks/commit-msg` is the shared commit message hook copied into
  every repository in this organization. See that file's header comment
  for installation instructions.

This repository does not ship application code.
