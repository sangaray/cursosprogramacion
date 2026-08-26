# Before & After

## CSS Pseudo-elements

They allow to insert content in a page without the need to put it in the HTML code
Spect the content generated to be befor the contente itself

- `::after` = is a contet tha also goes "after" origin order, for this reason it goes over the `::before` if they goes in a pile one over the other in a natural way.
  When I want to use both of them I have to use a `::before` and then a `::after`
- `content` = is what I want to put befor or after the element content
  **Values**
  - An URL = `url(/ruta/a/imagen.jpg)`. Images, a psudo-element could be a gradient
  - An empty string = `""`. It is useful to clear or insert images as background images
  - A counter = `counter(li)`. It is realy usefull to design list until the marker appears

## Other Pseudo-elements

- `::cue` = It is used to add subtitles to a video.
- `::first-letter` = It is used to add a first letter to a text.
- `::first-line` = It is used to add a first line to a text.
- `::placeholder` = It is used to add a placeholder to a form.
- `::selection` = It is used to add a selection to a text.

**Sintax**

```css
selector::pseudo-element {
  property: value;
}
```
