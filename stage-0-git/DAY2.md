# Day 2 — Git Branch, Merge, Conflict

## What I practiced
- Creating branches
- Committing meaningful changes
- Merging into main
- Creating and resolving merge conflicts
- Delete branch
## Commands I used
- git checkout -b <branch>
- git add .
- git commit -m "message"
- git merge <branch>
- git status
- git log --oneline --graph --all
- git switch (branch name)
- git branch (new branch name)
- git switch -c
- git branch -d 
## Merge conflict (what it is)
A merge conflict happens when Git cannot automatically combine changes.

## How I resolved it
1. Opened the conflicted file
2. Removed conflict markers (<<<<<<<, =======, >>>>>>>)
3. Combined the content into one final version
4. Ran git add and committed the resolution
