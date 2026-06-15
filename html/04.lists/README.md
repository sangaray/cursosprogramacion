# Lists

They are widely used for navigation menus, product reels, item cards, and footers.

## Classification of Lists:

**Unordered (ul)**
The ul element represents a list of items, where the order of the items is not important — that is, where changing the order would not materially change the meaning of the document.

- **Attributes**
  - type: Specifies the kind of marker to be used in the list. The following values are allowed:
    - "disc": A filled circle (●). This is the default value.
    - "circle": An empty circle (○).
    - "square": A filled square (■).
    - "none": No marker.

**Ordered (ol)**

- The ol element represents a list of items, where the items have been intentionally ordered, such that changing the order would change the meaning of the document. This is used to represent instructions, recipes, a ranking, or any other list where the order of the items is important.
- **Attributes**
  - Type Indicates the numbering type:
    'a' indicates lowercase letters,
    'A' indicates uppercase letters,
    'i' indicates lowercase Roman numerals,
    'I' indicates uppercase Roman numerals,
    and '1' indicates numbers (default).
    The type set is used for the entire list unless a different type attribute is used within an enclosed li element. - start: This integer attribute specifies the start value for numbering the individual list items. Although the ordering type of list elements might be Roman numerals, such as XXXI, or letters, the value of start is always represented as a number. To start numbering elements from the letter "C".
    **Note:** This attribute was deprecated in HTML4, but reintroduced in HTML5. - reversed: This Boolean attribute specifies that the items of the list are specified in reversed order.
    **Note:** In current days the ordered list is used to give order to the elements in a page

  **list item (li)**
  The li element represents a list item. If its parent element is an ol, ul, or menu element, then the element is an item of the parent element's list, as defined for those elements. Otherwise, the list item has no defined list-related relationship to any other li element.
  - **Attributes**
    - value: This attribute is only used when the li element is a child of an ol element. It specifies the ordinal value of the list item, which is used to determine the marker for that item and subsequent items in the list. The value must be a valid integer, and it can be positive, negative, or zero. If the value is positive, it represents the position of the list item in the ordered list, starting from 1. If the value is negative, it represents the position of the list item in reverse order, starting from -1 for the last item. If the value is zero, it represents a special case where the list item is not numbered and does not affect the numbering of subsequent items. This attribute isn't used anymore.

  **Descriptive (dl)**
  The dl element represents an association list consisting of zero or more name-value groups (a description list).
  - dt The dt element represents the term, or name, part of a term-description group in a description list (dl element).
  - dd The dd element represents the description, definition, or value, part of a term-description group in a description list (dl element). This label also works as a metadato, a value thas is invisible for the user but that is a part of our page. When someone looks for a term that is in our dt, the search engine will look into the dd element to find the definition of that term and show it in the search results.
