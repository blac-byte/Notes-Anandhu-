# HTML Lists (ul / ol / li)

## Purpose
- Used for **semantics & accessibility**
- Help screen readers understand grouped content
- Improve document structure (not just visuals)

---

## `<ul>` — Unordered List
- Stands for **Unordered List**
- Order of items **does NOT matter**
- Common use cases:
  - Navigation bars
  - Menus
  - Feature lists
  - Grouped links

### Example
```html
<nav>
  <ul>
    <li><a href="/">Home</a></li>
    <li><a href="/about">About</a></li>
  </ul>
</nav>
```


## `<ol>` — Ordered List
- Stands for **Ordered List**
- Order of items **matters**
- Automatically numbered

### Common use cases
- Steps / instructions
- Rankings
- Procedures
- Tutorials

### Example
```HTML
<ol>
  <li>Install dependencies</li>
  <li>Run the server</li>
  <li>Open the browser</li>
</ol>
```

## `<li>` — List Item

- Stands for **List Item**
- Must be a **child of `<ul>` or `<ol>
- Can contain:
    - Text
    - Links
    - Images
    - Divs
    - Nested lists

```html
<li>
  <a href="/contact">Contact</a>
</li>

```


## Accessibility Notes

- Screen readers announce:
    - "Navigation"
    - "List with 5 items"
- Improves keyboard navigation
- Better than using `<div>`s