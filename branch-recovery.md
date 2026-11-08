# Branch cleanup and recovery

## Update your local main after a merge

    git switch main
    git pull --ff-only
    git status

If a fast-forward is unavailable, inspect the local and remote histories before deciding how to reconcile them.

## Move uncommitted edits onto a practice branch

If you started editing on main and have not committed, run git switch -c docs/my-change. Then use git status and git diff to verify that your changes followed you.

## Undo a shared commit

Use git revert <commit> to create a new commit that reverses the earlier change. Review the resulting diff and open a pull request so the correction has a visible history.

[Back to the pull request workflow](README.md)
