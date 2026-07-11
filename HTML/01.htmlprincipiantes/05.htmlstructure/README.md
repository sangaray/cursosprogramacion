# HTML Structure

```
<!DOCTYPE html>
<html>
  <head>
    <title>TITLE</title>
  </head>
  <body>
    <h1></h1>
    <h2></h2>
    <a></a>
    <p></p>
    <img>
  </body>
</html>
```

- `<!DOCTYPE html>` = Stablishes the HTML standards for the document
- `<html>` = Represents the root of an HTML document
- `<head>` = Represents a collection of metadata about the document, including links
- `<body>` = Represents the main content of an HTML document

## HTML5 Structure

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>

## Elements

`<html>` = The root element of an HTML document
**Attributes**
Means identify an elment in a detailed way

- `lang` = Determineq the language of the document

  **Values**
  - `en` = Allows the page to be recognized as an English page
  - `es` = Allows the page to be recognized as a Spanish page

## Metadata

- `<meta>` = Information tha is not visible but is imprinted inside the page. It can represent information about the page.
  **Attributes**
  - `charset` = Define the encoding of the document. Allows any character from any language to be displayed

    **Values**
    - `UTF-8` = Unicode Transformation Format 8-bit character set. Allows any character from any language to be displayed. It allows to identify any character as an universal character.

  - `name` = Define the name of the metadata. It is used to identify the metadata.

    **Values**
    - `viewport` = Define the viewport of the page. It is used to define the size of the page regarding de screen of the device where it is displayed.

  - `content` = Define the content of the metadata. It is used to define the value of the metadata.

    **Values**
    - `width=device-width` = Define the width of the viewport as the width of the device.
    - `initial-scale=1.0` = Define the initial scale of the viewport as 1.0 or the zoom level of the page.

  - `http-equiv` = Define the HTTP header of the metadata. It is used to define the HTTP header of the metadata regading the compatibility of the page with different browsers

    **Values**
    - `X-UA-Compatible` = Define the compatibility of the page with different browsers.

  - `<title>` = Define the title of the document. It is displayed on te title bar or the tab in the browser.
