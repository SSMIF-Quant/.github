# .github

Org-wide defaults for `SSMIF-Quant`. GitHub falls back to whatever's in here for
any repo that doesn't define its own equivalent file.

## What's here

- `.github/ISSUE_TEMPLATE/task.yml` — the standard task form. Shows up as an
  option whenever someone clicks **New issue** in a repo that has no issue
  templates of its own (currently: every repo in the org).
- `.github/ISSUE_TEMPLATE/config.yml` — disables "Open a blank issue" so every
  new issue goes through the standard form.

## Note

This only applies to repos with **zero** issue templates of their own — if a
repo defines even one, GitHub uses only that repo's templates and ignores
these entirely.
