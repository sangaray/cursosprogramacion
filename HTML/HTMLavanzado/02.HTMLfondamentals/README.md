# HTML Fundamentals

## Tags

A tag is a keyword that is used to define the structure of an HTML document. Also called as elements.

## Elements

- `<!DOCTYPE>` = Declares the document type to be used.
- `<!DOCTYPE html>` = Declares the document type to be HTML5>`
- `<html>` = The root element of an HTML document.

  **Attributes**
  - `lang` = Specifies the language of the document.

    **Values**
    - `en` = English
    - `es` = Spanish
    - `fr` = French
    - `de` = German

- `<head>` = Contains information about the document.
- `<meta>` = Contains metadata about the document.

  **Attributes**
  `charset` = Define the encoding of the document. Allows any character from any language to be displayed

      **Values**
      - `UTF-8` = Unicode Transformation Format 8-bit character set. Allows any character from any language to be displayed. It allows to identify any character as an universal character.

  - `name` = Define the name of the metadata. It is used to identify the metadata.

    **Values**
    - `viewport` = Define the viewport of the document. It is used to define the size of the document regarding the screen of the device where it is displayed.

  - `content` = Define the content of the metadata. It is used to define the value of the metadata.

    **Values**
    - `width=device-width` = Define the width of the viewport of the document. It is used to define the width of the document regarding the screen of the device where it is displayed.
    - `initial-scale=1.0` = Define the initial scale of the viewport of the document. It is used to define the initial scale of the document regarding the screen of the device where it is displayed.
    - `shrink-to-fit=no` = Define the shrink-to-fit of the viewport of the document. It is used to define the shrink-to-fit of the document regarding the screen of the device where it is displayed.
    - `user-scalable=no` = Define the user-scalable of the viewport of the document. It is used to define the user-scalable of the document regarding the screen of the device where it is displayed.
    - `minimum-scale=1.0` = Define the minimum scale of the viewport of the document. It is used to define the minimum scale of the document regarding the screen of the device where it is displayed.

  - `http-equiv` = Define the HTTP header of the metadata. It is used to define the HTTP header of the metadata regading the compatibility of the document with different browsers.

    **Values**
    - `X-UA-Compatible` = Define the compatibility of the document with different browsers.
    - `IE=edge` = Define the compatibility of the document with Internet Explorer. It is currently out of use. IE it is not recommended to use nor used currently.

- `<title>` = Contains the title of the document. It is displayed on the title bar or the tab in the browser.
- `<body>` = Contains the content of the document.
- `<headr>` = Contains the header of the document.
- `<section>` = Contains the section of the document.
- `<article>` = Contains the article of the document.
- `lorem` = Contains the lorem of the document. It is used to generate random text.
- `<footer>` = Contains the footer of the document.
- `<link>` = Contains the link of the document. It is used to link the document to another document.

  **Attributes**
  - `rel` = Define the relationship of the link. It is used to define the relationship of the link.

    **Values**
    - `stylesheet` = Define the relationship of the link as stylesheet. It is used to define the relationship of the link as stylesheet.

  - `href` = Define the href of the link. It is used to define the href of the link.

## Shortcuts

- `Ctrl + S` = To save the document.

## CSS Selectors

A CSS selector is used to select HTML elements and apply styles to them. They can be tags, classes, IDs, or attributes.

- `*` = Selects all elements inside a HTML document.
- `htmltagname` = Selects all elements with the tag name "htmltagname".
- `.classname` = Selects all elements with the class name "classname".
- `#idname` = Selects all elements with the ID name "idname".

**Properties**

- `margin` = define the amount of space around an element.
- `padding` = define the amount of space between an element and its content.
- `width` = indicate the width of an element.
- `background` = allows to give a color o characteristic to the background of an element.
- `color` = allows to colorize an element.
- `padding-top` = define the space between the top of an element and its content.
- `padding-bottom` = define the space between the bottom of an element and its content.
- `display` = determine how an element is displayed.
- `border-randius` = indicate if an element has rounded corners.
- `margin-top` = define the space over the top of an element.
- `text-align` = indicate the alignment of the text inside an element.
- `font-family` = define the type of the font.
- `font-size` = determine the size of the font.
- `border-bottom` = indicate the parameters of the bottom border of an element.
- `float` = indicates the float position of an element.
- `line-height` = define the separation between lines of text.
- `text-transform` = allows to change the case of the text.
- `list-style` = define the format of a list bullet.
- `text-decoration` = indicate the decoration of the text.

**Values**

- `block` = This is a block element. It takes up the full width of the container and can contain other elements. It is used to create a block element. Is the default value for block elements.
- `auto` = with margin it centers the element.

**Pseudo-classes**

- `:hover` = This is a pseudo-class. It is used to select an element when the user hovers over it.
- `visited` = This is a pseudo-class. It is used to select an element when the user has visited it.

**Messurment Units**

- `em` = medidas en em = en em is a unit of measurement that is relative to the font size of the element it is applied to. It is used to specify the size of an element relative to the size of the font of the element it is applied to. 1em = 16px.
- `px` = is a unit of measurement that is relative to the size of the screen. It is used to specify the size of an element in pixels.
