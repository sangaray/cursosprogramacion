# Links and Images

## Links

They are text to navigate to another page or inside the same page or to another resource.

There are several types of links:

- Static Link
  **Definition:** A hardcoded URL that always points to the same fixed destination and does not change.
  **When used:** In static sites, navigation menus, footers, and content that rarely changes.
  **Example:** <a href="https://example.com/about">About</a>
- Dynamic Link
  **Definition:** A URL generated at runtime based on data, parameters, or user context.
  **When used:** In dynamic web applications, e-commerce platforms, blogs, and database-driven content.
  **Example:** /product/iphone-15-pro or /user/3421/profile
- Absolute Link
  **Definition:** A full URL that includes the protocol, domain, and complete path.
  **When used:** When linking to external websites or ensuring the link works from any page.
  **Example:** https://example.com/blog/post-1
- Relative Link
  **Definition:** A partial URL that is relative to the current page or root of the site.
  **When used:** For internal navigation within the same website (more maintainable).
  **Example:** /about or contact.html

# Link Element

- `<a>` = Link element. It is used to create links to other web resources.
  **Attributes**
- `href` = The URL of the linked resource.
- `target` = The target attribute specifies where to open the linked document.
  **Values**
  - `_blank` = Opens the linked document in a new window or tab.

# Image Element

- `<img>` = The img element is used to embed an image in an HTML document.
  **Attributes**
  - `src` = The src attribute specifies the URL of the image.
  - `alt` = The alt attribute specifies an alternate text for the image, if the image cannot be displayed.
  - `width` = The width attribute specifies the width of the image.
  - `height` = The height attribute specifies the height of the image.
- `<link>` = Indicates the relationship between the current document and an external resource.
  **Attributes**
  - `rel` = Indicates the relationship between the current document and the linked document.
    **Values**
    - `stylesheet` = The stylesheet relationship indicates that the linked document is a style sheet.
  - `href` = The href attribute specifies the URL of the linked document.
