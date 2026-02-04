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
## 2026-02-03 — Day 4 (Git)

### Focus
GitHub remote, push & pull, fetch, GitHub Pages

### What I did
- Connected the local repository to GitHub
- Practiced pushing and pulling changes
- Learned the difference between git fetch and git pull
- Created and deployed a demo using GitHub Pages

### Output
- Notes: [stage-0-git/DAY4.md](stage-0-git/DAY4.md)
- Live demo deployed via GitHub Pages

### Problems / Fixes
- Confusion between fetch and pull → resolved by testing both commands on remote changes

### Next
Team collaboration: Pull Request, Fork, gitignore, tags
