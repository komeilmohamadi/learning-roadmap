# Day 7 — CSS Selectors, Box Model, Display & Flexbox Basics

## What I practiced
- Internal CSS styling and how it differs from inline CSS
- Core CSS selectors (class, id, combinators, attribute selectors)
- Understanding the box model (margin / padding / default spacing)
- Display modes (block / inline / inline-block / none)
- Flexbox fundamentals (parent/child layout)
- Pseudo-classes for interactive and structural styling
- Practicing selectors with CSS Diner-style exercises
- Continued English learning

---

## CSS Styling Methods

### Inline CSS (review)
- Using the `style=""` attribute directly on HTML elements
- Useful for learning, but not scalable

### Internal CSS (new)
- Using a `<style>` block inside the `<head>`
- Writing rules for multiple elements in one place
- Cleaner than inline for learning and small pages

---

## CSS Selectors (Core)

### Basic selectors
- Type selector (tag selector)
- Class selector (`.class`)
- ID selector (`#id`)
- Difference between class vs id:
  - Class can be reused multiple times
  - ID should be unique per page

### Combinators (relationships)
- Descendant selector (inside)
- Child selector (direct child)
- Adjacent sibling selector (direct next element)
- General sibling selector (all following siblings)

### Universal selector
- Selecting all elements (`*`)
- Selecting all children inside a container (`container *`)

### Selector lists
- Selecting multiple elements with comma `,` (OR selector)

### Attribute selectors
- Exact match (`=`)
- Starts with (`^=`)
- Ends with (`$=`)
- Contains (`*=`)

---

## Box Model & Layout Concepts
- Margin (outer spacing)
- Padding (inner spacing)
- Default browser margins on some tags (e.g., headings)
- Using DevTools (Firefox / Firebug-style inspection) to visualize:
  - margin area
  - padding area
  - element size and spacing

---

## Display Property
- `block`: takes full width by default
- `inline`: takes only needed width (does not accept width/height normally)
- `inline-block`: inline behavior + accepts width/height
- `none`: hidden (not rendered)

---

## Flexbox Basics
- Using `display: flex` on the parent container
- Parent/child layout terminology
- Main axis alignment with `justify-content`:
  - start / center / end
  - space-between / space-around / space-evenly
- Cross axis alignment with `align-items` (and basic understanding of vertical alignment)
- Centering with margin auto (review)

---

## Pseudo-classes (Selectors with states/positions)
- `:hover` (mouse over)
- `:active` (during click)
- `:first-child`
- `:last-child`
- `:nth-child(n)` including odd/even
- `:only-child` (important for “single child” cases)

---

## Language Practice
- English practice continued (consistency maintained)

---

## Reflection
Learning selectors deeply (including combinators and pseudo-classes) made CSS much clearer and helped me understand how real layouts are built and controlled.
