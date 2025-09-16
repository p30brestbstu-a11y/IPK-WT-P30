# Contributing

Thanks for helping improve IPK-WT-P30!

- Fork the repo and create a feature branch.
- Follow the folder structure described in README.
- For documentation changes, run markdownlint locally if possible (or rely on CI).
- Open a pull request with a clear description and link to related task.
- Review at least two classmates' PRs.

## Commit messages
Use concise, imperative subject lines. Examples: "docs: update task_01 readme", "chore: add issue templates".

## Pull requests
- Keep PRs focused and small.
- Include screenshots for UI/docs changes when helpful.

## Branch & PR policy
- Default branch: `main`.
- Use feature branches: `students/<id>/task_xx/<short-topic>` or `chore/<topic>`.
- Protected `main` requires:
  - 1 approving review from the Code Owner (@andreiNiasiuk).
  - Code owner review required when touching owned paths.
  - Passing required status checks: Lint.
  - Up-to-date branch before merge (no red CI).
  - Linear history and squash merges only.
- After merge: branches are auto-deleted.
- Force pushes and direct pushes to `main` are disallowed.
