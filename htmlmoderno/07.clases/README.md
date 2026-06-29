# Classes

A space-separated list of the classes of the element. Classes allows CSS and JavaScript to select and access specific elements via the class selectors or functions like the method

## Unique class

It is an attribute that is often used to point to a class name in a style sheet. It is used to apply a style to an element.
The name of the class is case sensitive, it recognizes if the name is in upper or lower case as different names.

## Multiclass

This is a list of several classes separated by a space.
The important thing here isn't the name of the element but the name of the class

## Naming Classes and Elements

The name must describe the function, not just the color or appearance.

```html
<div class="box2"></div>
<div class="red"></div>
```

```html
<div class="main-container"></div>
<div class="btn-primary"></div>
```

## The Format

The name must be written in lowercase and separated by hyphens. Not use camelCase or snake_case.

```html
<div class="main-container"></div>
<div class="myObject"></div>
<div class="main_container"></div>
```

## Semantics

The name must indicate the element's function.

<!-- prettier-ignore -->
```html
<div class="red-text"></div> not ok
<div class="error-message"></div> ok
<div class="large-button"></div> not ok
<div class="primary-button"></div> ok
```

## BEM Methodology

BEM (Block Element Modifier) is a naming convention for classes in CSS. It is used to create a more organized and maintainable codebase. Exist a set of rules that guide the naming of classes with specific words on it.

```html
<div class="card">
  <h2 class="card__title">HTML Course</h2>
  <p class="card__description">Learn from scratch</p>
  <button class="card__button card__button--primary">Enroll</button>
</div>
```

card => block

card\_\_title => element

card\_\_button--primary => modifier

## IDs

Defines a unique identifier (ID) which must be unique in the whole document. Its purpose is to identify the element when linking (using a fragment identifier), scripting, or styling (with CSS).
