# Multiple Backgrounds

## CSS Properties

- `background` = The background property is a shorthand property for the background-color, background-image, background-repeat, background-attachment, background-position, and background-size properties.

  **Structure**
  - `background: url(path) position / size no-repeat`
    - `url(path)` = The path to the image file.
    - `position` = The position of the background image.

      **Values**
      - `top` = The background image is positioned at the top of the element.
      - `right` = The background image is positioned at the right of the element.
      - `bottom` = The background image is positioned at the bottom of the element.
      - `left` = The background image is positioned at the left of the element.
      - `center` = The background image is positioned in the center of the element.

  - `size` = The size of the background image.
  - `no-repeat` = The background image is not repeated.

  **For more than one image**
  - `background: url(path1) position1 / size1 no-repeat, url(path2) position2 / size2 no-repeat, url(path3) position3 / size3 no-repeat;`

  - `background-size` = The size of the background image.

    **Values**
    - `cover` = The background image is resized to cover the entire element.
    - `contain` = The background image is resized to fit the element while maintaining its aspect ratio.
    - `auto` = The background image is not resized.
    - `xpx` = The size of the background image in pixels.

  - `background-clip` = The background-clip property specifies whether the background should be clipped to the content box, padding box, or border box.

    **Values**
    - `border-box` = The background is clipped to the border box.
    - `padding-box` = The background is clipped to the padding box.
    - `content-box` = The background is clipped to the content box.
