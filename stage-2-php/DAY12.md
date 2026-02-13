# Day 12 — PHP Functions, Scope & Built-in Utilities

## What I practiced
- Structuring complex data using nested arrays
- Writing reusable functions
- Working with parameters and return values
- Understanding scope rules
- Preserving values using static
- Using arrow functions for short expressions
- Working with important built-in string and array functions

---

## Nested Arrays

### Goal
Organize multiple similar entities (e.g., users) in a structured way.

### Concept
- Each entity is stored as its own array
- All entities are grouped inside a larger array
- Improves readability and structure

### Key Insight
Index starts from 0, so `$array[1]` refers to the second item.

---

## Functions

### Goal
Avoid repetition and improve maintainability.

### Why Functions Matter
- Reduce duplicated code
- Improve readability
- Make updates easier
- Break large logic into manageable pieces

### Important Concept
A function must be **called** to execute.
Defining ≠ Executing.

---

## return Keyword

### Critical Concept
`return` does NOT print.
It sends the result back to where the function was called.

To see the result:
- Use `echo`
- Or store it in a variable

Think of a function as:
Input → Process → Return Output

---

## Parameters

### Goal
Allow external values to enter the function.

### Key Idea
Parameters make functions dynamic and reusable.

---

## Rest Operator (...$nums)

### Problem It Solves
When the number of arguments is unknown.

### Concept
- `...$nums` collects all inputs into an array
- Must always be the LAST parameter

---

## Spread Operator (...$array)

### Purpose
Expand elements of an array.

### Use Cases
- Copying arrays
- Merging arrays
- Passing array elements individually

---

## Scope

### Why Scope Matters
Determines where variables can be accessed.

---

### Global Scope
Defined outside functions.

⚠ Overusing globals can:
- Create hidden dependencies
- Make debugging difficult

---

### Local Scope
Defined inside a function.
Only accessible within that function.

---

## global Keyword

Allows access to global variables inside a function.

⚠ Best Practice:
Avoid relying heavily on `global` in professional architecture.

---

## static Keyword

### Problem It Solves
Normally, function variables reset after execution.

### static Behavior
- Preserves variable value between calls
- Created once and reused

---

## Arrow Functions (fn)

### Purpose
Short and clean one-line functions.

### Use When
- Simple logic
- One-line return
- Readability remains clear

Not suitable for complex multi-line logic.

---

# Important Built-in String Functions

## strlen
Returns string length.

## strpos
Finds position of substring.
Returns false if not found.

## substr
Extracts part of a string.

## trim / ltrim / rtrim
Removes extra spaces.

## strtoupper / strtolower
Changes case of letters.

## explode
Converts string to array.

## implode
Converts array to string.

---

# Important Built-in Array Functions

## count / sizeof
Count array elements.

## is_array
Check if variable is array.

## in_array
Check if value exists in array.

## array_merge
Merge arrays.

## array_values
Extract only values from associative arrays.

## array_reverse
Reverse array order.

## array_sum
Sum numeric array values.

## array_push / array_unshift
Add element to end / beginning.

## array_pop / array_shift
Remove element from end / beginning.

## array_map
Apply operation to each element and return new array.

## array_slice
Extract part of array.

---

## Final Summary
Today I learned how to structure data with nested arrays, write reusable functions, understand scope and memory behavior with static, use arrow functions for concise logic, and leverage PHP’s built-in string and array functions for faster and cleaner development.
