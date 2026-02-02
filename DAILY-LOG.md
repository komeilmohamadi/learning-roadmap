## 2026-02-02 — Day 2 (Git)

### Focus
Git Branching, Merge, and Conflict Resolution

### What I did
- Created a feature branch and made meaningful commits
- Merged changes into main
- Simulated a merge conflict and resolved it manually
- Cleaned up merged branches

### Output
- Notes: stage-0-git/DAY2.md
- Repo updated with merge + conflict resolution commits

### Commands practiced
git checkout -b <branch>
git switch <branch>
git merge <branch>
git branch -d <branch>

### Problems / Fixes
- Faced an add/add conflict in DAY2.md → resolved by manually combining contents and committing.

### Next
Day 3: rebase, stash, clean history

## 2026-02-02 — Day 3 (Git)

### Focus
Git diff, restore/reset/revert, stash

### What I did
- Practiced git diff in multiple modes
- Learned how to undo changes safely using restore, reset, and revert
- Navigated commit history using HEAD~N
- Practiced managing unfinished work with git stash

### Output
- Notes: [stage-0-git/DAY3.md](stage-0-git/DAY3.md)

### Problems / Fixes
- git restore did not work on untracked files → learned the difference between tracked and untracked files
- Case-sensitive file path issues → fixed by using correct file paths

### Next
Finish GitHub & Remote workflow (clone, pull, fetch, PR, fork, pages)
