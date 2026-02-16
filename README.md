# Learning Roadmap

This repository documents my journey to become a job-ready backend and full-stack developer.

## Goals
- Learn Git & GitHub professionally
- Build real-world projects
- Prepare for future job opportunities

## Day 2 — Git Branch, Merge & Conflict

Practiced professional Git workflows including branching, merging, and resolving merge conflicts using a real repository.

### What I learned
- Creating and managing branches
- Switching between branches
- Merging feature branches into main
- Understanding fast-forward vs merge commit
- Creating and resolving merge conflicts
- Cleaning up merged branches

### Implementation
- Notes & practice: [`stage-0-git/DAY2.md`](stage-0-git/DAY2.md)
- Conflict simulation and resolution committed to main branch

## Day 3 — Git Diff, Restore/Reset/Revert & Stash

Practiced reviewing changes and safely undoing mistakes using advanced Git commands.

### What I learned
- Using git diff to compare changes before committing
- Understanding the differences between restore, reset, and revert
- Navigating commit history using HEAD~N
- Managing unfinished work with git stash

### Implementation
- Notes & practice: [`stage-0-git/DAY3.md`](stage-0-git/DAY3.md)

### Reflection
Learning how to review and undo changes safely is essential for maintaining a clean Git history and collaborating with confidence.

## Day 4 — GitHub Remote, Fetch/Pull & Pages

Practiced working with remote repositories, synchronizing changes, and deploying a live demo using GitHub Pages.

### What I learned
- Connecting local and remote repositories
- Pushing and pulling commits
- Understanding the difference between fetch and pull
- Deploying projects using GitHub Pages

### Implementation
- Notes & practice: [`stage-0-git/DAY4.md`](stage-0-git/DAY4.md)

### Reflection
Understanding remote workflows and using fetch before pull helps avoid conflicts and keeps collaboration safe.

## Day 5 — GitHub Collaboration, README & Versioning

Completed advanced GitHub workflows including documentation, collaboration, and versioning.

### What I learned
- Writing professional README files using Markdown
- Using Markdown syntax for headings, lists, tables, links, and code blocks
- Adding repository badges with shields.io
- Managing collaborators in private repositories
- Working with Pull Requests from feature branches
- Forking repositories and contributing via Pull Requests
- Using .gitignore to exclude unnecessary files
- Creating and managing Git tags for versioning and releases

### Implementation
- Notes & practice: [`stage-0-git/DAY5.md`](stage-0-git/DAY5.md)

### Reflection
Learning collaboration workflows and versioning practices made me more confident to work on real-world and open-source projects.

## Day 6 — HTML Foundations & Environment Setup

Started **Stage 1 (HTML & CSS)** and focused on setting up the development environment and learning core HTML concepts.

### What I learned
- Efficient usage of Visual Studio Code (search, replace, extensions, shortcuts)
- Understanding file types used in web development (.html, .css, .js, .php)
- Core HTML structure and essential tags
- Difference between container tags and self-closing tags
- HTML attributes (global vs tag-specific)
- Basic CSS concepts and inline styling

### Implementation
- Notes & practice: [`stage-1-html-css/DAY6.md`](stage-1-html-css/DAY6.md)

### Reflection
Building a strong foundation in HTML and tooling is essential before moving into layout, styling, and JavaScript.
## Day 7 — CSS Selectors, Box Model, Display & Flexbox Basics

Expanded CSS fundamentals with internal styling, advanced selectors, and layout basics including display modes and flexbox.

### What I learned
- Internal CSS using `<style>` and clean rule structure
- CSS selectors (class, id, combinators, universal, attribute selectors)
- Box model (margin/padding/default spacing) and DevTools inspection
- Display modes (block/inline/inline-block/none)
- Flexbox fundamentals (justify-content, align-items)
- Pseudo-classes (:hover, :active, :first-child, :last-child, :nth-child, :only-child)

### Implementation
- Notes & practice: [`stage-1-html-css/DAY7.md`](stage-1-html-css/DAY7.md)
## Day 8 — CSS Flexbox Deep Dive & Practical Layouts

Focused on strengthening layout skills by going deeper into Flexbox and building practical, real-world layouts.

### What I learned
- Flexbox axis model (main axis vs cross axis)
- `flex-direction`, `flex-wrap`, and `flex-flow`
- `justify-content` vs `align-items` vs `align-content`
- Using `gap` instead of margins in flex layouts
- Flex item properties (`flex-grow`, `flex-shrink`, `flex-basis`)
- Proper centering techniques with Flexbox
- Common Flexbox layout patterns (navbar, cards, columns)

### Implementation
- Notes & practice: [`stage-1-html-css/DAY8.md`](stage-1-html-css/DAY8.md)

### Reflection
Flexbox finally feels predictable instead of trial-and-error.
Understanding axes and item behavior made layout debugging much easier.

## Day 10 — PHP Basics: Environment, Variables, Data Types & Arrays

Started **Stage 2 (PHP)** by setting up the local environment and learning the core building blocks of PHP programming.

### What I learned
- Setting up a local PHP development environment
- PHP syntax basics and PHP tags
- Variables and naming conventions
- Data types in PHP
- Working with strings and concatenation
- Operators and arithmetic logic
- Arrays and basic array operations

### Implementation
- Notes & practice: [`stage-2-php/DAY10.md`](stage-2-php/DAY10.md)

### Reflection
Understanding PHP fundamentals made backend concepts clearer.
These basics form the foundation of every real-world PHP and backend application.

## Day 11 — PHP Control Flow: Conditionals, Logic, Switch, Loops & Associative Arrays

Continued **Stage 2 (PHP)** by learning how to control program flow using conditions, comparisons, logical operators, switches, loops, and associative arrays.

### What I learned
- Conditional statements (`if`, `elseif`, `else`) for decision making
- Comparison operators and the difference between `==` and `===`
- Logical operators (`&&`, `||`, `!`) for combining conditions
- Ternary operator for short, readable one-line conditions
- `switch` for handling many known cases cleanly
- Loops (`for`, `foreach`, `while`, `do...while`) and when to use each
- Associative arrays (key/value) for meaningful data structure

### Implementation
- Notes & practice: [`stage-2-php/DAY11.md`](stage-2-php/DAY11.md)

### Reflection
Control flow is where PHP starts to feel like real programming.
With conditions, loops, and associative arrays, I can now build logic-driven scripts instead of just printing values.

## Day 12 — PHP Functions, Scope, Static, Arrow Functions & Built-in Functions

Continued Stage 2 (PHP) by learning how to structure reusable logic using functions, manage variable scope, understand memory behavior with static, and use important built-in PHP string and array functions.

### What I learned
- Nested arrays for structured multi-entity data
- Creating reusable functions and understanding function calls
- Parameters and return values
- Rest and Spread operators
- Variable scope (global vs local)
- Using `static` inside functions
- Arrow functions for short expressions
- Important PHP string and array built-in functions

### Implementation
- Notes & practice: [`stage-2-php/DAY12.md`](stage-2-php/DAY12.md)

### Reflection
Functions and scope are where PHP becomes structured and maintainable.
Understanding memory behavior and built-in utilities makes development faster and cleaner.

## Day 13 — PHP Superglobals, Forms, Sessions & Database Fundamentals

Learned how PHP communicates with the outside world using superglobals and started the database journey (DBMS, SQL, MySQL basics).

### What I learned
- Difference between global and superglobal variables
- Handling forms using `$_GET`, `$_POST`, and `$_FILES`
- Using `isset()` safely with form inputs
- Understanding `$_SERVER`
- Cookie vs Session and state management
- Database fundamentals (DBMS vs RDBMS)
- SQL basics and query types
- Database structure concepts (Primary Key, utf8mb4, VARCHAR vs TEXT)

### Implementation
- Notes & practice: [`stage-2-php/DAY13.md`](stage-2-php/DAY13.md)

### Reflection
This day marked the transition from basic PHP scripts to real web backend concepts, including user input handling and database architecture.


## Day 14 — PHP MySQL Connection, CRUD & Prepared Statements

Learned how PHP connects to MySQL using mysqli, how to execute queries, fetch results, and prevent SQL Injection using prepared statements.

### What I learned
- Connecting to MySQL using `mysqli_connect`
- Executing queries with `mysqli_query`
- Fetching results using `mysqli_fetch_all`
- Understanding result types (MYSQLI_ASSOC, NUM, BOTH)
- Performing CRUD operations (INSERT, SELECT, UPDATE, DELETE)
- Importance of `WHERE` in UPDATE and DELETE
- Understanding SQL Injection
- Using Prepared Statements for secure queries

### Implementation
- Notes & practice: [`stage-2-php/DAY14.md`](stage-2-php/DAY14.md)

### Reflection
This day transformed database knowledge into real backend implementation.
Understanding prepared statements is a major step toward writing secure and production-ready PHP code.
