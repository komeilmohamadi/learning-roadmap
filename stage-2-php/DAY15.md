# Day 15 — SQL Query Building Essentials

## What I practiced
- Understanding SQL clauses (not “classes”)
- Writing cleaner SELECT queries with column selection and aliases
- Sorting results using ORDER BY
- Pagination using LIMIT and OFFSET
- Working with NULL correctly
- Using aggregate functions for analysis
- Filtering using IN, BETWEEN, and LIKE
- Memorizing the correct clause order

---

## Clauses (Correct Terminology)
In SQL, each section is called a **Clause**, not a Class.

Examples:
- SELECT clause
- FROM clause
- WHERE clause
- ORDER BY clause

(Class is an OOP concept; Clause is SQL terminology.)

---

## Aliases (AS)

### What It Does
Alias renames a column or expression only in the query result.

✅ Important:
Aliases do not change database structure.
They only affect the output of SELECT.

### Common Use Cases
- Computed columns (e.g., currency conversion, tax)
- Report-friendly column names
- Readable output for front-end/API

---

## Avoiding SELECT *

### Why It’s Not Recommended
- Retrieves unnecessary data (slower)
- Larger responses
- Risk of exposing sensitive columns
- Output changes unexpectedly when new columns are added

✅ Professional rule:
Select only the columns you need.

---

## ORDER BY (Sorting)

### Purpose
Sort query results.

### Directions
- ASC (default) → ascending
- DESC → descending

### Multi-Column Sorting
Sort by one column first, then use a second column as tie-breaker.

Use case:
Newest items first, then most expensive.

---

## LIMIT & OFFSET (Pagination)

### LIMIT
Restricts number of rows returned.

### OFFSET
Skips a number of rows before applying LIMIT.

### Pagination Formula
OFFSET = (page - 1) * perPage

---

## NULL Handling

### NULL Meaning
NULL is “no value” (not 0, not empty string).

### Correct Checks
- IS NULL
- IS NOT NULL

⚠ Using `= NULL` is incorrect in SQL.

---

## Aggregate Functions (MIN / MAX / SUM / AVG)

Used for calculations on sets of rows.

- MAX → highest value
- MIN → lowest value
- SUM → total
- AVG → average

✅ Note:
Aggregate queries often return a single row because the output is computed.

---

## IN / NOT IN

### Purpose
Cleaner alternative to multiple OR conditions.

IN checks if a value is inside a list.
NOT IN checks if a value is not inside a list.

---

## BETWEEN

### Purpose
Filter values within a range.

Common for:
- Age ranges
- Date ranges
- Price ranges

Usually includes both ends of the range.

---

## LIKE (Pattern Matching)

### Purpose
Search text using patterns.

### Common Patterns
- Starts with → prefix%
- Ends with → %suffix
- Contains → %text%

⚠ Performance note:
LIKE with %...% can be slow on large datasets (later solved with indexing/full-text search).

---

## Clause Order (Must Memorize)

Standard order:
1) SELECT
2) FROM
3) WHERE
4) ORDER BY
5) LIMIT
6) OFFSET

This order helps avoid mistakes and write predictable queries.

---

## Final Summary
Today I improved my SQL skills by learning aliases, selecting only needed columns, sorting and paginating results, handling NULL correctly, using aggregate functions, and applying practical filters (IN, BETWEEN, LIKE). I also reinforced the correct clause order for writing clean, real-world queries.