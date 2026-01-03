
## Core Principle
> Use elements that describe **meaning**, not appearance.

---

## Page Structure (Top-Level)
- [ ] `<html lang="en">` set correctly
- [ ] `<head>` contains title, meta, links
- [ ] One `<main>` per page
- [ ] `<header>` for page/section headers
- [ ] `<footer>` for page/section footers

---

## Navigation
- [ ] Use `<nav>` for primary navigation
- [ ] Navigation links grouped inside `<ul><li>`
- [ ] Avoid using `<div>` for nav menus
- [ ] Multiple `<nav>` allowed (header, footer, sidebar)

```html
<nav>
  <ul>
    <li><a href="#">Home</a></li>
  </ul>
</nav>
```

## Content Sections
- [ ] Use `<section>` for **thematic grouping**
- [ ] Each `<section>` has a heading (`h2–h6`)
- [ ] Use `<article>` for **standalone content**
- [ ] Don’t use `<section>` just for styling

---


Headings
- [ ] One `<h1>` per page
- [ ] Navigation links grouped inside `<ul><li>`
- [ ] Avoid using `<div>` for nav menus
- [ ] Multiple `<nav>` allowed (header, footer, sidebar)

---

## Lists
- [ ] Use `<ul>` when order does not matter
- [ ] Use `<ol>` when order matters
- [ ] `<li>` only inside `<ul>` or `<ol>`
- [ ] Use lists for navbars, menus, grouped items
- [ ] Avoid lists for purely visual layout

---

## Forms & Inputs
- [ ] Every input has a `<label>`
- [ ] `<label for>` matches input `id`
- [ ] Use correct input `type` (`email`, `number`, etc.)
- [ ] Use `name` attribute for backend submission
- [ ] Use `<fieldset>` + `<legend>` for grouped inputs
- [ ] Inputs have accessible placeholders (optional)
- [ ] Validation done via HTML where possible

---

## Buttons & Links
- [ ] Use `<a>` for navigation
- [ ] Use `<button>` for actions
- [ ] Do NOT use `<div>` or `<span>` as buttons
- [ ] Buttons inside forms use `<button>`
- [ ] Links must have meaningful text

---

## Images
- [ ] All `<img>` elements have `alt`
- [ ] Use `alt=""` for decorative images
- [ ] Use `<figure>` + `<figcaption>` when caption needed
- [ ] Do NOT put meaningful content only in background images

---

## Text Semantics
- [ ] Use `<strong>` for importance
- [ ] Use `<em>` for emphasis
- [ ] Avoid `<b>` and `<i>` for meaning
- [ ] Use `<time>` for dates/times
- [ ] Use `<code>` for inline code
- [ ] Use `<pre>` for code blocks

---

## Accessibility
- [ ] Page makes sense without CSS
- [ ] Logical reading order
- [ ] Keyboard navigation works
- [ ] No click handlers on non-interactive elements
- [ ] Semantic HTML used before ARIA
- [ ] ARIA only when necessary


## Common Anti-Patterns (Avoid)

- ❌ `<div>` everywhere
- ❌ Clickable `<div>`s
- ❌ Styling instead of semantics
- ❌ Missing labels
- ❌ Skipping heading levels


> If CSS is removed, the page should still make sense.