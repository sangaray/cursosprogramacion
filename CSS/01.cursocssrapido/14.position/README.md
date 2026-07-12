# Position

It is a CSS property that allows you to position an element relative to its normal position. It is used to create a floating effect on an element.
It allows to create more complex layouts.

## Properties

- `position`: Sets the position of an element.

  **Values**
  - `static`: The default value. The element is not positioned. If there are several elementes with this position each one lives with each other.
  - `relative`: The element is positioned relative to its normal position.
  - `absolute`: The element is positioned relative to the viewport. The elements needs to have a parent with `position: relative`. The absolute element should be positioned inside its parent element.
  - `fixed`: The element is positioned relative to the browser window.

- `top`: Sets the top position of an element.
- `left`: Sets the left position of an element.
- `right`: Sets the right position of an element.
- `bottom`: Sets the bottom position of an element.

**Note**

- When we use `top, left, right, bottom` the position of the element is relative to the parent element, an it can lose parts of its content.
- These can be use to create a parent element.
