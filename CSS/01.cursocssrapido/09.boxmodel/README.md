# Box Model

This means that the width and height of an element are determined by the content inside it, not by the padding, border, or margin. This model is used to create a box that contains elements or an element that contains other elements.

## Properties

- `width` = The width property sets the width of an element.
- `height` = The height property sets the height of an element. Currently it isn't supported in all browsers, the height should be automatically calculated, and not used manualy.
- `padding`= Represents the internal space between the content and the border of an element, am internal border.
- `border` = Represents the boundary border of an element.
- `margin` = Represents the external space between the border and the margin of an element. Used to separate boxes or elements, an external border.

  **Positions**
  They can be used in all the above properties
  - `top` = The top property sets the top position of an element.
  - `right` = The right property sets the right position of an element.
  - `bottom` = The bottom property sets the bottom position of an element.
  - `left` = The left property sets the left position of an element.

## Shorthand Properties

They are used to set all the above properties at the same time. -`padding` = The padding property is a shorthand property for the padding-top, padding-right, padding-bottom, and padding-left properties.

- `margin` = The margin property is a shorthand property for the margin-top, margin-right, margin-bottom, and margin-left properties.+
- `border` = The border property is a shorthand property for the border-top, border-right, border-bottom, and border-left properties.

**Extructure:** border: width style color;

**Values:**

- `style`
  - `none:` default value, indicates that there is no border. hidden: the border is not visible but is there, ocuppying space.
  - `dotted` = it made of dots,
  - `dashed` = it made of dashes,
  - `solid` = it made of lines, double = it made of two lines -`inset` (Sunken / Pressed): It makes the element look "pushed in" or embedded into the page.
  - `outset` (Raised / Popping Out): The direct opposite of inset; it makes the element look like a classic 3D button that stands out and is ready to be clicked.
  - `groove` (Carved / Channel): It simulates a small groove, channel, or trench carved into the surface around the element. -`ridge` (Crest / Extruded): The direct opposite of groove. It simulates a raised ridge or mountain-like border that lifts up from the page, similar to an old picture frame.

  **Note:** In modern web design, these native 3D borders are rarely used because they mimic an outdated 90s aesthetic. Current frontend development achieves 3D depth, realism, and elegance by using a `solid` border combined with the `box-shadow` property, which offers pixel-perfect control over light, blur, and shadows.

**Example:** property: top right bottom left (padding: 20px 30px 40px 50px) or property: top/bottom left/ right (padding: 10px 20px) or property: top/right/bottom/left (padding: 20px). This applies to every property that define the four positions.
