
# Day 2 — Git Branch, Merge & Conflict

## What I practiced
- Creating branches
- Committing meaningful changes
- Merging feature branches into main
- Switching between branches
- Deleting branches
- Creating and resolving merge conflicts

## Commands I used
- git checkout -b <branch>
- git switch -c <branch>
- git switch <branch>
- git branch <branch>
- git branch -d <branch>
- git add .
- git commit -m "message"
- git merge <branch>
- git status
- git log --oneline --graph --all

## Merge conflict (what it is)
A merge conflict happens when Git cannot automatically combine changes from different branches.

## How I resolved it
1. Opened the conflicted file
2. Removed conflict markers (<<<<<<<, =======, >>>>>>>)
3. Combined the content into a final version
4. Staged the file and committed the resolution
