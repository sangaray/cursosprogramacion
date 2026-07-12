# Floating Boxes

Floating boxes are containers that are positioned relative to the normal flow of the document. They can be used to create sidebars, navigation menus, and other elements that should float next to the main content of the document.

## Properties

- `float`: Sets the floating behavior of an element.

  **Value**:
  - `left`= The element floats to the left of the normal flow of the document.
  - `right`= The element floats to the right of the normal flow of the document.
  - `none` = The element does not float.
  - `inline` = The element floats to the left of the normal flow of the document.

  ## Note
  - If you add padding, borde this will increment the size of the element.
  - If you add padding to an element that has a floating behavior, the padding will be added to the top and bottom of the element, and not to the left or right.

  - `box-sizing` = Sets the box model type for an element.

    **Values**
    - `border-box` = the border-box value is used to set the size of an element to include the content, padding, and border.
    - `content-box` = the content-box value is used to set the size of an element to include only the content and padding, and not the border.
