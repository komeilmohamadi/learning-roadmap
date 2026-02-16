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

## 2026-02-04 — Day 5 (Git)

### Focus
GitHub collaboration, README documentation, Fork workflow, and versioning

### What I did
- Practiced writing professional README files using Markdown
- Learned core Markdown syntax (headings, lists, tables, links, images, code blocks)
- Added repository badges using shields.io
- Worked with Pull Requests and branch-based workflows
- Managed collaborators in private repositories
- Practiced Fork workflow and contributing via Pull Requests
- Used .gitignore to keep the repository clean
- Created and managed Git tags for versioning

### Output
- Notes: stage-0-git/DAY5.md
- Repository finalized and prepared for version 1 release

### Next
Start HTML & CSS fundamentals (beginning of full-stack development)

## 2026-02-05 — Day 6 (HTML & CSS)

### Focus
HTML fundamentals and development environment setup

### What I did
- Entered Stage 1 (HTML & CSS)
- Reviewed Visual Studio Code features for efficient development
- Practiced working with different file types (.html, .css, .js, .php)
- Learned core HTML structure and essential tags
- Studied tag categories (container vs self-closing)
- Practiced using attributes (global and specific)
- Learned CSS basics and inline styling concepts

### Output
- Notes: stage-1-html-css/DAY6.md
- Stage 1 folder structure finalized

### Language
- English study: 5 sessions completed

### Next
HTML semantic tags, forms, and structure practice
## 2026-02-08 — Day 7 (HTML/CSS)

### Focus
Internal CSS, selectors, box model, display, flexbox basics, pseudo-classes

### What I did
- Practiced internal CSS using a `<style>` block
- Learned and practiced core CSS selectors (class, id, combinators, universal)
- Worked with attribute selectors and selector combinations
- Studied box model concepts (margin, padding, default spacing)
- Practiced display modes (block, inline, inline-block, none)
- Learned flexbox basics (justify-content, align-items) with parent/child layout thinking
- Practiced pseudo-classes (:hover, :active, :first-child, :last-child, :nth-child, :only-child)

### Output
- Notes: stage-1-html-css/DAY7.md

### Notes
- 2026-02-07: No study session (rest day)

### Next
Continue CSS layout: flexbox practice + small UI section (header/cards) using clean structure
## 2026-02-08 — Day 8 (Stage 1: HTML & CSS)

### Focus
Deep dive into CSS Flexbox and practical layout building.

### What I did
- Reviewed Flexbox axes and alignment logic
- Practiced container and item properties
- Built common layouts using Flexbox (centering, navbar, cards)
- Debugged layouts using browser DevTools
- Fixed common Flexbox mistakes

### Output
- Flexbox practice notes and examples
- Day 8 documentation: `stage-1-html-css/DAY8.md`

### Next
Start responsive layouts and prepare for CSS Grid.

## 2026-02-09 — Day 9 (Stage 1: HTML & CSS)

### Focus
Deep dive into CSS selectors, relationships, and pseudo-classes.

### What I did
- Practiced universal and grouping selectors
- Worked with AND selectors and selector specificity
- Learned descendant, child, and sibling selectors
- Used attribute selectors with different matching patterns
- Practiced pseudo-classes for interaction and structure
- Improved selector logic and targeting accuracy

### Output
- CSS selector notes and explanations
- Day documentation: `stage-1-html-css/DAY9.md`

### Next
Move into responsive design with media queries and real layout scenarios.

## 2026-02-10 — Day 10 (Stage 2: PHP)

### Focus
Learning PHP fundamentals and setting up the local development environment.

### What I did
- Installed and configured PHP local environment
- Learned PHP syntax and structure
- Practiced variables and naming conventions
- Worked with data types and strings
- Practiced operators and arithmetic logic
- Learned array basics and operations

### Output
- PHP fundamentals documentation
- Day notes: `stage-2-php/DAY10.md`

### Next
Learn conditional statements (if / else) and comparison operators.

## 2026-02-11 — Day 11 (Stage 2: PHP)

### Focus
Learning PHP control flow: conditions, comparisons, logic, switch, loops, and associative arrays.

### What I did
- Practiced `if / elseif / else` to control execution flow
- Learned comparison operators and the difference between `==` and `===`
- Used logical operators (`&&`, `||`, `!`) to combine conditions
- Practiced ternary operator for short conditional output
- Learned `switch` for handling multiple known cases
- Practiced loops (`for`, `foreach`, `while`, `do...while`)
- Worked with associative arrays (key/value)

### Output
- Control flow & data structures notes
- Day documentation: `stage-2-php/DAY11.md`

### Next
Work on functions and reusability (parameters, return values), and start building small PHP mini-projects.

## 2026-02-12 — Day 12 (Stage 2: PHP)

### Focus
Functions, scope, memory behavior, and built-in utilities in PHP.

### What I did
- Structured data using nested arrays
- Created reusable functions with parameters and return values
- Practiced rest and spread operators
- Learned global vs local scope
- Used static to preserve values between calls
- Practiced arrow functions
- Explored important PHP string and array built-in functions

### Output
- Functions & utilities documentation
- Day notes: `stage-2-php/DAY12.md`

### Next
Start building mini-projects using functions and arrays (e.g., simple user system or calculator project).

## 2026-02-13 — Day 13 (Stage 2: PHP)

### Focus
Superglobals, form handling, session management, and database fundamentals.

### What I did
- Studied global vs superglobal variables
- Worked with $_GET, $_POST, $_FILES, $_SERVER
- Learned safe form handling using isset()
- Understood Cookie vs Session
- Learned DBMS vs RDBMS concepts
- Studied SQL and main query types
- Reviewed PHP database connection methods

### Output
- Superglobals & database fundamentals documentation
- Day notes: `stage-2-php/DAY13.md`

### Next
Implement real PHP-to-MySQL connection and execute first database queries.


## 2026-02-14 — Day 14 (Stage 2: PHP)

### Focus
Connecting PHP to MySQL, executing CRUD operations, and securing queries.

### What I did
- Connected to database using mysqli_connect
- Executed SELECT queries and fetched results
- Practiced INSERT, UPDATE, DELETE operations
- Learned importance of WHERE clause
- Understood SQL Injection risks
- Implemented Prepared Statements for secure queries

### Output
- Database connection & secure query documentation
- Day notes: `stage-2-php/DAY14.md`

### Next
Refactor database logic into reusable functions and start building a mini user management system.
