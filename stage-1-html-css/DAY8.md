# Day 8 — CSS Flexbox Deep Dive & Practical Layouts

## What I practiced
- Deep understanding of Flexbox layout system
- Building real-world layouts using Flexbox
- Debugging layouts using browser DevTools
- Replacing hacky CSS with proper Flexbox solutions

---

## Core Concepts Review

### Flexbox Axes
- **Main Axis**: controlled by `flex-direction`
- **Cross Axis**: perpendicular to main axis

```css
.container {
  display: flex;
  flex-direction: row; /* row | column */
}
```

Understanding axes made alignment rules predictable instead of confusing.

---

## Container Properties

### justify-content (Main Axis)
```css
justify-content: flex-start;
justify-content: center;
justify-content: space-between;
justify-content: space-around;
justify-content: space-evenly;
```

### align-items (Cross Axis)
```css
align-items: stretch;
align-items: center;
align-items: flex-start;
align-items: flex-end;
```

### align-content (Multi-line only)
Works only when `flex-wrap` is enabled.

```css
flex-wrap: wrap;
align-content: space-between;
```

---

## Item Properties

### flex-grow / flex-shrink / flex-basis
```css
.item {
  flex: 1 1 200px;
}
```

- `flex-grow`: how much space an item can take
- `flex-shrink`: how it shrinks when space is limited
- `flex-basis`: initial size before growing/shrinking

---

## Gap vs Margin
Using `gap` for spacing between items:

```css
.container {
  display: flex;
  gap: 16px;
}
```

Cleaner and safer than margins in Flexbox layouts.

---

## Common Layout Patterns

### Centering (The Right Way)
```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

### Navbar Layout
- Logo aligned left
- Menu aligned right
- Vertical centering handled by Flexbox

### Card Layout
- Equal-height cards
- Responsive wrapping with `flex-wrap`

---

## Debugging with DevTools
- Enabled Flexbox overlay in browser DevTools
- Visualized main/cross axes
- Inspected item sizes and spacing

---

## Common Mistakes Fixed
- Confusing `align-items` with `justify-content`
- Forgetting axis direction when switching to `column`
- Overusing margins instead of Flexbox alignment
- Using absolute positioning for simple layouts

---

## Reflection
Flexbox no longer feels like trial and error.
By understanding axes and item behavior, layout problems became logical and much easier to debug.

## Day 9 — CSS Selectors Deep Dive (Combinators, Attributes & Pseudo-Classes)

Focused on deeply understanding CSS selectors, their relationships, and how styles are applied based on structure, attributes, and user interaction.

### What I learned
- Universal selector and selecting all elements
- Grouping selectors using comma (OR selector)
- AND selector (tag + class)
- Descendant vs child selectors
- Sibling selectors (adjacent and general)
- Attribute selectors and their matching patterns
- Pseudo-classes for interaction and element position
- Choosing the correct selector based on HTML structure

### Implementation
- Notes & practice: [`stage-1-html-css/DAY9.md`](stage-1-html-css/DAY9.md)

### Reflection
Understanding selectors deeply made CSS predictable.
Instead of trial and error, I can now precisely target elements based on structure and behavior.
