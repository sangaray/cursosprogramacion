# El Video

## Elements

- `<video>`= The video element is used to embed video content in HTML.
- `<iframe>`= The iframe element is used to embed a web page in HTML or an embedded video.

## Attributes

- `src` = The src attribute specifies the URL of the video file.
- `controls` = The controls attribute specifies that the user should get some controls for the video.
- `width` = The width attribute specifies the width of the video player.
- `onclick` = The onclick attribute specifies a script to be run when the user clicks the video player.

## Functions

- `play()` = The play() method plays the video.
- `pause()` = The pause() method pauses the video.
- `requestFullscreen()` = The requestFullscreen() method requests that the video player enter fullscreen mode.
- `frameborder` = The frameborder attribute specifies the width of the border around the video player.

## Methods

- `getElementById()` = The getElementById() method returns the element that has the ID attribute with the specified value.
- `width` = The width property sets or returns the width of the video player.

## Notes

**Note 1**
To use the iframe element in HTML, to call a youtube video it is needed to use the next link syntax:

https://www.youtube.com/embed/tk-74lmkacs?controls=0

instead of:

https://youtu.be/6TewE1BCZ_M?list=PLg9145ptuAijj9GoHPTcYT8IoQAOchM-n

**Note 2**

In the function completa(), to get a real fullscreen it needed to use the next code:

```javascript
function completa() {
  // Fullscreen API with vendor prefixes for compatibility
  if (mi_video.requestFullscreen) {
    mi_video.requestFullscreen();
  } else if (mi_video.webkitRequestFullscreen) {
    /* Safari */
    mi_video.webkitRequestFullscreen();
  } else if (mi_video.msRequestFullscreen) {
    /* IE11 */
    mi_video.msRequestFullscreen();
  }
}
```
