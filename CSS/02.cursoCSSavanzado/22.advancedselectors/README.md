# Advanced Selectors

## Selectors Types

**Children**

- `p > span` (Direct Child Combinator): Applies the style exclusively to `<span>` elements that are direct children (first level) of a `<p>`. If the `<span>` is wrapped inside another element (such as `<strong>`, `<a>`, or `<div>`) within the paragraph, this style will not affect it.
- `p span` (Descendant Combinator): Applies the style to any `<span>` inside a `<p>`, regardless of how many levels deep it is nested or what other elements wrap it.

**adjacent**

- `h1 + h2` (Adjacent Sibling Combinator): Applies the style to the `<h2>` element that is immediately after a `<h1>`.

**sibbling**

- `h1 ~ p` (General Sibling Combinator): Applies the style to all `<p>` elements that are siblings of a `<h1>` element starting in the first h1.

**attribute**

- `[class="highlight"]` (Attribute Selector): Applies the style to any element with the class attribute set to "highlight".
  The main difference lies in how they target elements in the HTML and how they react when an element has multiple classes.

**Diference between class and attribute selectors:** -`.highlight` (Class selector): Checks if the word `highlight` is present within the element's list of classes. If the element has additional classes (for example, `<p class="card highlight active">`), it works and applies the style. -`[class="highlight"]` (Exact attribute selector): Requires the value of the `class` attribute to be exactly and exclusively `"highlight"`. If the element has additional classes (such as `<p class="card highlight active">`), it will not work because the entire string does not match exactly.

**Comparison example:**

```html
<!-- Case A: Has only one class -->
<p class="highlight">Text A</p>

<!-- Case B: Has multiple classes -->
<p class="card highlight">Text B</p>
```

**Note**
on specificity: Both selectors have the exact same specificity in CSS (0,1,0), so if applied to the same element, the one written lower in the CSS file will take priority
