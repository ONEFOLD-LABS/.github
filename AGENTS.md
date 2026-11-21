# ONEFOLD-LABS/.github – guide for AI agents

This file is for AI coding agents and the people who run them. `CLAUDE.md` points here. This
repository holds the organisation profile (`profile/README.md`, shown on
https://github.com/ONEFOLD-LABS) and shared defaults; see `README.md`.

## Rules

- **A person is accountable** for every commit and pull request an agent produces. Read the diff
  before you open a pull request.
- **`main` changes only through a pull request.** A merge changes the public organisation page
  at once.
- **One change at a time, linear history.** Start each change on a new branch from the current
  `origin/main`, open its pull request, and merge it with **Rebase and merge** as soon as it is
  reviewed (and CI is green, where there is CI); then delete the branch and start the next change
  from the new `main`. Do not stack pull requests on top of each other and do not leave branches,
  worktrees or pull requests lying around. If `main` moved, `git rebase origin/main` (never merge
  `main` into the branch); `main` has no merge commits.
- **Assets come from `ONEFOLD-LABS/brand`.** `profile/assets/` holds copies of its logos and app
  icons; change them there and copy them over, never edit the copies.
- **Clean room.** Do not imitate or name other products or their vendors.
- **Report only what ran**, and keep secrets and personal data out of the repository.

## Commits and pull requests

- Commit messages in **English**, imperative subject (≤ 72 chars), body explaining what and why.
- Branch names: `feat/…`, `fix/…`, `docs/…`.
