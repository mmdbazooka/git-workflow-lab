# Git Workflow Lab

A small practice repository for Git branches, pull requests, and issue triage.

## Practice a pull request

1. Run git switch main, then git pull --ff-only.
2. Create a practice branch with git switch -c docs/my-first-change.
3. Edit a file, run git diff to review the change, then stage and commit the intended file.
4. Push with git push -u origin docs/my-first-change.
5. Open a pull request against main. Summarize what changed and how you checked it.
6. In Files changed, check that the diff matches your intent. Merge when the change is ready.

See [Branch cleanup and recovery](branch-recovery.md) for common follow-up steps.
