## Restore / Reset / Revert (Summary)

### git restore
- `git restore --staged <file>`: Unstage a file (keeps changes)
- `git restore <file>`: Discard local changes in a file (dangerous)

### git reset
- `git reset --soft <commit>`: Move HEAD back, keep changes staged
- `git reset <commit>` (mixed): Move HEAD back, keep changes unstaged
- `git reset --hard <commit>`: Delete changes (dangerous)

### git revert
- `git revert <commit>`: Safe undo by creating a new commit
- `git revert --continue`: Continue after resolving conflicts during revert
