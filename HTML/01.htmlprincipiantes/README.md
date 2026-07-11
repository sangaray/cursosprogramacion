# Emmet Cheat Sheet

## What is Emmet?

**Emmet** is a shortcut system for writing HTML and CSS code efficiently. It expands short abbreviations into full HTML and CSS structures, reducing the time required to write repetitive code.

---

# Why Use Emmet?

- 🚀 **Faster HTML & CSS Coding** – Saves time by expanding short codes into full syntax.
- ✅ **Error Reduction** – Reduces typos and manual errors.
- 📖 **Improved Readability** – Makes code easier to understand.
- 💻 **Works in Multiple Editors** – Compatible with VS Code, Sublime Text, Atom, WebStorm, and more.

---

# Enabling Emmet in Visual Studio Code

Emmet is pre-installed in Visual Studio Code, but you may need to enable it for specific file types.

## Enabling Emmet for HTML and CSS

Emmet works automatically in `.html` and `.css` files.

## Enabling Emmet for Other File Types

If you need Emmet in JavaScript, PHP, or other file types:

1. Open **VS Code Settings** (`Ctrl + ,`).
2. Search for **Emmet: Include Languages**.
3. Add the following configuration to your `settings.json` file:

```json
{
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "php": "html"
  }
}
```

After saving the file, Emmet will also work inside JavaScript and PHP files.

---

# HTML Emmet Cheat Sheet

The following abbreviations help generate HTML faster.

## Basic HTML Boilerplate

### Abbreviation

```text
!
```

Press **Tab** or **Enter** to generate:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

---

## Creating HTML Elements

| Emmet                    | Expands To                   |
| ------------------------ | ---------------------------- |
| `h1{Hello World}`        | `<h1>Hello World</h1>`       |
| `p{This is a paragraph}` | `<p>This is a paragraph</p>` |
| `a{Click me}`            | `<a href="">Click me</a>`    |

---

## Nesting Elements

### Abbreviation

```text
ul>li*3
```

Expands to:

```html
<ul>
  <li></li>
  <li></li>
  <li></li>
</ul>
```

---

### Abbreviation

```text
nav>ul>li*3>a{Link $}
```

Expands to:

```html
<nav>
  <ul>
    <li><a href="">Link 1</a></li>
    <li><a href="">Link 2</a></li>
    <li><a href="">Link 3</a></li>
  </ul>
</nav>
```

---

## Using IDs and Classes

| Emmet                 | Expands To                                |
| --------------------- | ----------------------------------------- |
| `div#main`            | `<div id="main"></div>`                   |
| `div.container`       | `<div class="container"></div>`           |
| `section.hero.banner` | `<section class="hero banner"></section>` |

---

# CSS Emmet Cheat Sheet

Emmet also speeds up writing CSS.

## Basic Properties

| Emmet  | Expands To       |
| ------ | ---------------- |
| `w100` | `width: 100px;`  |
| `h50`  | `height: 50px;`  |
| `m20`  | `margin: 20px;`  |
| `p10`  | `padding: 10px;` |

---

## Text and Font Properties

| Emmet       | Expands To                   |
| ----------- | ---------------------------- |
| `fs16`      | `font-size: 16px;`           |
| `fw700`     | `font-weight: 700;`          |
| `c#333`     | `color: #333;`               |
| `bg#f4f4f4` | `background-color: #f4f4f4;` |

---

## Flexbox Shortcuts

| Emmet   | Expands To                        |
| ------- | --------------------------------- |
| `d:f`   | `display: flex;`                  |
| `fd:c`  | `flex-direction: column;`         |
| `ai:c`  | `align-items: center;`            |
| `jc:sb` | `justify-content: space-between;` |

---

# Advanced Emmet Cheat Sheet

## Multiplication (`*`)

Creates multiple elements.

### Abbreviation

```text
div*5
```

Expands to:

```html
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
```

---

## Numbering (`$`)

Automatically increments numbers.

### Abbreviation

```text
ul>li.item$*3
```

Expands to:

```html
<ul>
  <li class="item1"></li>
  <li class="item2"></li>
  <li class="item3"></li>
</ul>
```

---

## Grouping (`()`)

Groups elements together.

### Abbreviation

```text
(div>h2{Title})+(div>p{Description})
```

Expands to:

```html
<div>
  <h2>Title</h2>
</div>

<div>
  <p>Description</p>
</div>
```

---

# Customizing Emmet in Visual Studio Code

You can customize Emmet behavior through your VS Code settings.

## Changing the Expand Key

By default, **Tab** expands Emmet abbreviations.

To enable or change this behavior:

1. Open **Settings** (`Ctrl + ,`).
2. Search for **Emmet: Trigger Expansion On Tab**.
3. Enable the option.

---

## Defining Custom Abbreviations

Add the following to your `settings.json` file:

```json
{
  "emmet.variables": {
    "lang": "en"
  },
  "emmet.syntaxProfiles": {
    "html": {
      "tag_case": "lower"
    }
  }
}
```

---

# Emmet Interview Cheat Sheet

## What is Emmet, and why is it used?

Emmet is a shortcut system that helps developers write HTML and CSS much faster by expanding abbreviations into complete code.

---

## How do you create an Emmet abbreviation for a navigation bar?

```text
nav>ul>li*3>a{Link $}
```

---

## Can you use Emmet in JavaScript files in VS Code?

Yes.

Enable it by adding the following configuration to `settings.json`:

```json
{
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  }
}
```

---

## How does `$` work in Emmet?

The `$` symbol automatically increments numbers in:

- Class names
- IDs
- Text content

Example:

```text
.item$*3
```

Produces:

```html
<div class="item1"></div>
<div class="item2"></div>
<div class="item3"></div>
```

---

# Conclusion

This Emmet cheat sheet serves as a quick reference for writing HTML and CSS efficiently in Visual Studio Code.

Mastering Emmet abbreviations will:

- 🚀 Speed up development.
- 📖 Improve code readability.
- ⚡ Reduce repetitive typing.
- 💻 Increase overall productivity.
