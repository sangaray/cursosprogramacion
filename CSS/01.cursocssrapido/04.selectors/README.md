# Selectors

They are used to select HTML elements and apply styles to them.

**Structure**

```css
selector {
  property: value;
}
```

## Selector Types

**Universal**
It is used to select all HTML elements in a document.
`*` = Selects all HTML elements in a document.

**By Tag**
These are used to select HTML elements by their tag name.

- `tag-name` = Selects all HTML elements with a tag name of "tag-name".

**Descendent**
These are used to select HTML elements that are descendants of another element.

- `tag1 tag2` = Selects all `tag2` elements that are descendants of `tag1` elements.

**By Class**
These are used to select HTML elements by their class attribute.

- `.class-name` = Selects all HTML elements with a class attribute value of "class-name".

**By ID**
These are used to select HTML elements by their id attribute.

- `#id-name` = Selects all HTML elements with an id attribute value of "id-name".
