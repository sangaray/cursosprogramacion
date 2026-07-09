# ID & Classes

## ID

This attribute is a unique name for an HTML element. It must be unique within the HTML document. It is used to identify the element when writing JavaScript or CSS.

### Properties

- `#`= The hash symbol (#) is used to identify an element by its id. The value of the id attribute must be unique within the HTML document. The id attribute is case-sensitive.
- `#id-name` = The id attribute specifies a unique name for an HTML element. The value of the id attribute must be unique within the HTML document. The id attribute is case-sensitive. It is used in css to select an element by its id to style it.
- `text-align` = The text-align property specifies the horizontal alignment of the text inside an element.
- `background` = The background property specifies the background color of an element. -`color` = The color property specifies the color of the text.
- `font-size` = The font-size property specifies the size of the text.

## Classes

It is a name that dosoen't need to be unique. This attribute is used to identify an element by its class. It is used in CSS to select elements by their class to style them.

- `.` = The period (.) is used to identify an element by its class. The value of the class attribute must be unique within the HTML document. The class attribute is case-sensitive.
- `.class-name` = The class attribute specifies a class for an HTML element. The value of the class attribute is a space-separated list of class names.

## Combined Selectors

- `.selector1, selector2` = This is a combined selector that selects all elements with class "selector1" and class "selector2".

**Notes**

- If there is a container element with a class, then all elements with class "container" will be selected. It is recomended to use the class into the container if it has only one element inside
