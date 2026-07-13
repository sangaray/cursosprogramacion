# Links II and Lists

## Lists

There are two kind of lists:

1. Unordered lists = they are lists that do not have a specific order

### Elements

- `<ul>` = unordered list. It is a list of items that do not have a specific order.

2. Ordered lists = they are lists that have a specific order

### Elements

- `<ol>` = ordered list. It is a list of items that have a specific order.

### For Both of Them

- `<li>` = list item. It is an item in a list.

  **Properties**
  - `list-style` = it is used to style the type of the bullet of a list.

    **Values**
    - `none` = it is used to remove the bullet points from the list.
    - `disc` = it is used to add a disc bullet to the list.
    - `circle` = it is used to add a circle bullet to the list.
    - `square` = it is used to add a square bullet to the list.

  - `list-style-image` = it is used to add an image as a bullet to the list.

**Notes**

- We can apply a style to serverals elements at the same time using `element or class or id 1`, `element or class or id 2`, `element or class or id 3`, etc. But the condition is that the elements should be related to each other.
-
- When creating a menu using an unordered list, it is recommended to use `display: block` for the list items, this way the `<a>` element will ocuppy the whole width of the list item.
