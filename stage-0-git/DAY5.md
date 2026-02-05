````md
# Day 5 — GitHub Collaboration, README, Fork & Versioning

## What I practiced
- Writing professional README files
- Using Markdown (MD) syntax
- Adding badges with shields.io
- Managing collaborators
- Working with Pull Requests
- Forking repositories and contributing via PR
- Using .gitignore
- Creating and managing Git tags (versioning)

---

## README.md
The README file is the main documentation of a project and typically includes:
- Project description
- Installation instructions
- Required packages
- Usage guide
- Demo or live links

Markdown (`.md`) is used to format README files.

---

## Markdown Syntax (Examples)

### Headings
```md
# Heading 1
## Heading 2
### Heading 3
```

### Text formatting
```md
**Bold**
*Italic*
***Bold & Italic***
`Inline code`
```

### Lists
```md
- First item
- Second item
  - Nested item
  - Nested item
```

### Code block
```javascript
function test() {
  console.log("Komeil");
}
```

### Links
```md
[Visit my website](https://example.com)
```

### Images
```md
![My image](https://example.com/image.png)
```

### Clickable image (image as a link)
```md
[![My image](https://example.com/image.png)](https://example.com)
```

### Tables
```md
| Name   | Age |
|--------|-----|
| Komeil | 26  |
| Ali    | 29  |
```

---

## Badges (using shields.io)

Badges are used to display repository information such as:
- Repository size
- Star count

```md
![Repo Size](https://img.shields.io/github/repo-size/komeilmohamadi/learning-roadmap)
![Stars](https://img.shields.io/github/stars/komeilmohamadi/learning-roadmap)
```

---

## Collaboration & Pull Requests

A typical collaboration workflow:
- Create a feature branch
- Push the branch to GitHub
- Open a Pull Request (PR) into `main`
- Review, merge, and delete the branch

```md
- Created feature branches
- Opened Pull Requests instead of pushing directly to main
- Reviewed and merged Pull Requests
- Deleted merged branches
- Added collaborators to private repositories
- Accepted collaboration invitations
```

---

## Fork Workflow

Fork is commonly used when you don't have write access to the original repository:
- Fork the repo into your account
- Make changes in your fork
- Push changes to your fork
- Open a PR to the original repository

```md
- Forked a repository
- Made changes in the forked repository
- Pushed changes to a personal GitHub account
- Created a Pull Request to the original repository
- Learned how maintainers review and merge contributions
```

---

## Remote & Clone Notes

Check existing remotes:
```bash
git remote -v
```

Clone is used when you want a fresh local copy of a repository (no local remote configured yet):
```bash
git clone <repo-url>
```

---

## .gitignore

Used to prevent committing unnecessary files (example):
```gitignore
node_modules/
.env
.DS_Store
```

Helpful tool:
```text
https://gitignore.io
```

---

## Git Tags (Versioning)

### Lightweight tag
```bash
git tag v1
```

### Annotated tag (recommended for releases)
```bash
git tag -a v1 -m "Version 1 - Git & GitHub roadmap completed"
```

### Show tag details
```bash
git show v1
```

### Tag a previous commit
```bash
git tag v1 <commit-hash>
```

### Delete a tag
```bash
git tag -d v1
```

### Push tags to remote
```bash
git push origin v1
git push origin --tags
```

---

## Reflection
Completing Git & GitHub collaboration workflows, documentation, and versioning provides a solid foundation for working on real-world and open-source projects.
````
