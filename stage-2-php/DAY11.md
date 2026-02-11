# Day 11 — PHP Control Flow & Data Structures

## What I practiced
- Writing conditions to control execution flow
- Using comparison and logical operators correctly
- Choosing between if/else and switch based on use-case
- Iterating through data using loops
- Using associative arrays for meaningful key/value data

---

## Conditionals (if / elseif / else)

### Goal
Control the program path based on different conditions.

### Key Concepts
- `if` runs when a condition is true
- `elseif` adds additional conditions
- `else` runs when none of the above conditions match

### Notes
- Use clear conditions
- Keep branches readable and minimal when possible

---

## Comparison Operators

### Goal
Compare two values to decide what should happen next.

### Key Concepts
- `==` checks value equality (type is not considered)
- `===` checks value AND type equality (strict comparison)

### Common Operators
- `>` greater than
- `<` less than
- `>=` greater than or equal
- `<=` less than or equal
- `!=` not equal (value)
- `!==` not equal (value or type)

### Takeaway
Prefer strict comparison (`===`) when you want safe and predictable behavior.

---

## Logical Operators

### Goal
Combine multiple conditions into one decision.

### Operators
- `&&` (AND): both conditions must be true
- `||` (OR): at least one condition must be true
- `!` (NOT): negates a condition

### Takeaway
Logical operators help build real-world validations and multi-condition rules.

---

## Ternary Operator

### Goal
Write simple conditions in one line (while keeping readability).

### Concept
- Useful for short decisions
- Should not replace complex if/else logic

---

## switch Statement

### Goal
Handle many known cases more cleanly than long if/elseif chains.

### Key Concepts
- Each `case` represents a possible match
- `break` prevents falling into the next case
- `default` handles unexpected values

### Takeaway
Use `switch` when you have many fixed options for a single value.

---

## Loops

### for loop
**Goal:** Use when the number of iterations is known.

### foreach loop
**Goal:** Best choice for arrays.

**Why it matters**
- Designed for arrays
- Cleaner and less error-prone than manual indexing
- Stops automatically when the array ends

### while loop
**Goal:** Use when you don't know the number of iterations in advance.

**Concept**
- Checks the condition before each run

### do...while loop
**Goal:** Ensure the loop runs at least once.

**Concept**
- Runs once, then checks the condition

---

## Associative Arrays (Key/Value)

### Goal
Store data using meaningful keys instead of numeric indexes.

### Key Concepts
- Keys represent meaning (e.g., `name`, `age`)
- Values store the actual data

### Takeaway
Associative arrays make data easier to read, maintain, and scale.

---

## Final Summary
> Today I learned how to control program flow using conditions, comparisons, logic, switches, and loops.
> I also practiced associative arrays to store structured and meaningful data.
> These concepts are essential for writing real-world PHP applications.
