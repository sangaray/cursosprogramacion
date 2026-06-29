# Image Optimization

Currently use images is about accessibility, performance and adaptability, not only use de img tag and wait for the best.

## Perfomance

We will see four points:
**- Responsive Design**
They should be adapted to any device currently in use.
**- Performance**
The page works faster if the images is light and load easily.
**- Accessibility**
The images must be available for people even if they have any disability.
**- SEO**
To help the positioning of the page in the search engine.

## img Tag

# Image Element and Attributes

### Code

```html
<img src="image.jpg" alt="Description of the image" />
```

**Breakdown**

- img $\rightarrow$ Image Tag
- src="image.jpg" $\rightarrow$ Image Path
- alt="..." $\rightarrow$ Alternative Text (Accessibility and SEO). image textual description.

**Image Types**

- jpg in this case we need to handle the weight of the image.
- png these can have transparent background
- gif these are animated images
- tiff this are vectors and are lighter then the others

**Attributes**

- src The image URL. This attribute is mandatory for the `<img>` element. On browsers supporting srcset, src is treated like a candidate image with a pixel density descriptor 1x unless an image with this pixel density descriptor is already defined in srcset, or unless srcset contains 'w' descriptors.
- alt This attribute defines an alternative text description of the image.

**Note:** Browsers do not always display the image referenced by the element. This is the case for non-graphical browsers (including those used by people with visual impairments), if the user chooses not to display images, or if the browser cannot display the image because it is invalid or an unsupported type. In these cases, the browser may replace the image with the text defined in this element's alt attribute. You should, for these reasons and others, provide a useful value for alt whenever possible.

**Note:** Omitting this attribute altogether indicates that the image is a key part of the content, and no textual equivalent is available. Setting this attribute to an empty string (alt="") indicates that this image is not a key part of the content (decorative), and that non-visual browsers may omit it from rendering.

-loading Indicates how the browser should load the image.

- lazy Indicates that the image should be loaded lazily. The image will not be downloaded until it is visible in the viewport.
- eager Indicates that the image should be loaded immediately. The image will be downloaded even if it is not visible in the viewport.

- decoding Provides an image decoding hint to the browser. The allowed values are:
  - sync Decode the image synchronously for atomic presentation with other content.
  - async Decode the image asynchronously to reduce delay in presenting other content.
  - auto The browser will decide whether to decode the image synchronously or asynchronously.

  **Note:** Loading="lazy" and deocding="async" should be used together and always specialy if you have a lot of images in your webpage.

**Redimensioning the Image**

- width The intrinsic width of the image in pixels.
- height The intrinsic height of the image in pixels.

- srcset The srcset attribute is a list of one or more strings separated by commas indicating a set of possible image sources for the user agent to use. Each string is composed of:
  - a URL to an image,
    optionally, whitespace followed by one of:
  - A width descriptor, or a positive integer directly followed by 'w'. The width descriptor is divided by the source size given in the sizes attribute to calculate the effective pixel density.
  - A pixel density descriptor, which is a positive floating point number directly followed by 'x'.
    If no descriptor is specified, the source is assigned the default descriptor: 1x.
    It is incorrect to mix width descriptors and pixel density descriptors in the same srcset attribute. Duplicate descriptors (for instance, two sources in the same srcset which are both described with '2x') are also invalid.
    The user agent selects any one of the available sources at its discretion. This provides them with significant leeway to tailor their selection based on things like user preferences or bandwidth conditions.

  - sizes A list of one or more strings separated by commas indicating a set of source sizes. Each source size consists of:
  - a media condition. This must be omitted for the last item.
  - a source size value.
    Source size values specify the intended display size of the image. User agents use the current source size to select one of the sources supplied by the srcset attribute, when those sources are described using width ('w') descriptors. The selected source size affects the intrinsic size of the image (the image’s display size if no CSS styling is applied). If the srcset attribute is absent, or contains no values with a width (w) descriptor, then the sizes attribute has no effect.

## Source Tag

The source element allows authors to specify multiple alternative media resources for media elements. It does not represent anything on its own.
It is used when I have an image format that is not compatible with the browser

**Attributes**

- src The image URL. This attribute is mandatory for the `<img>` element. On browsers supporting srcset, src is treated like a candidate image with a pixel density descriptor 1x unless an image with this pixel density descriptor is already defined in srcset, or unless srcset contains 'w' descriptors.

- type The MIME-type of the resource, optionally with a codecs parameter. See RFC 4281 for information about how to specify codecs.

**figcaption Tag**

- figcaption The figcaption element represents a caption or legend for the rest of the contents of the figcaption element's parent figure element, if any.
