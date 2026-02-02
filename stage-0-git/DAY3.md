# Day 3 — Git Diff, Restore, Reset, Revert & Stash

## What I practiced
- Reviewing changes using git diff
- Navigating commit history with HEAD~N
- Undoing changes using restore, reset, and revert
- Managing unfinished work using git stash

## git diff
- `git diff` → working directory vs staging area
- `git diff --staged` → staging area vs last commit
- `git diff HEAD` → working directory vs last commit
- `git diff <commit1>..<commit2>` → differences between commits
- `git diff <branch1>..<branch2>` → differences between branches

## Navigating commit history
- `git log --oneline --graph --decorate --all`
- `git checkout HEAD~<number>` (detached HEAD state)

## Restore / Reset / Revert

### git restore
- `git restore --staged <file>`: remove file from staging area (keep changes)
- `git restore <file>`: discard local changes in a file (dangerous)

### git reset
- `git reset --soft <commit>`: move HEAD back, keep changes staged
- `git reset <commit>` (mixed): move HEAD back, keep changes unstaged
- `git reset --hard <commit>`: remove changes completely (dangerous)

### git revert
- `git revert <commit>`: safely undo a commit by creating a new commit
- `git revert --continue`: continue revert after resolving conflicts

## git stash
- `git stash push -m "message"`: save uncommitted changes
- `git stash list`: list all stashes
- `git stash apply`: apply stash and keep it
- `git stash pop`: apply stash and remove it
- `git stash drop stash@{n}`: remove a specific stash
- `git stash clear`: remove all stashes (dangerous)

## Reflection
Using git diff before committing and choosing the correct undo strategy (restore, reset, or revert) helps keep the repository clean and safe when working alone or in a team.
