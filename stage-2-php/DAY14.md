# Day 14 — PHP MySQL Connection & Secure Queries

## What I practiced
- Connecting PHP to MySQL using mysqli
- Executing SELECT queries and fetching results
- Performing CRUD operations
- Using WHERE with logical operators
- Preventing SQL Injection with Prepared Statements

---

## Connecting to Database (mysqli_connect)

### Required Parameters
- Hostname
- Username
- Password
- Database name

### Important Concept
If connection fails, execution should stop.
Always check connection result before proceeding.

---

## Database Workflow in PHP

Typical process:
1. Write SQL query
2. Execute using mysqli_query
3. Fetch results (for SELECT)
4. Use data inside PHP

---

## SELECT Query

Example meaning:
SELECT * FROM table_name

- SELECT → read data
- * → all columns
- FROM → specific table

### Fetching Results

mysqli_query only executes.
To retrieve data, we must fetch.

---

### Fetch Modes

#### MYSQLI_ASSOC (Recommended)
- Returns associative array
- Column names used as keys
- Best readability for real projects

#### MYSQLI_NUM
- Numeric indexes only
- Less readable

#### MYSQLI_BOTH
- Both numeric and associative keys
- More memory usage

---

## CRUD Operations

### INSERT (Create)
Adds new records.
Returns true/false.

---

### UPDATE (Modify)
Modifies existing records.

⚠ Critical:
Always use WHERE.
Without WHERE, all rows will be updated.

---

### DELETE (Remove)

Deletes records.

⚠ Without WHERE:
Entire table will be deleted.

---

## SQL Injection

### What It Is
When user input is directly inserted into SQL query,
malicious input can modify the query logic.

### Example Risk
User manipulates URL input to change query behavior.

---

## Prepared Statements

### Why It Matters
Separates SQL structure from user data.

### How It Works
1. Write query with placeholders (?)
2. Prepare statement
3. Bind parameters
4. Execute safely
5. Fetch result

### Key Benefit
User input is treated as data, not executable SQL.

---

## WHERE Clause

Filters data precisely.

### Logical Operators
- AND → both conditions must be true
- OR → at least one condition true
- != → not equal

### Parentheses
Use parentheses to control logical priority and avoid unexpected results.

---

## Final Summary

Today I implemented real database interaction using mysqli.
I learned how to execute queries, fetch results properly, perform CRUD operations safely, and prevent SQL Injection using prepared statements.
Understanding WHERE logic and secure query building is essential for backend development.
