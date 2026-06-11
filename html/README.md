# HTML5 - ACTUALIZED

## TEXT LABELS

### Headings:

- h1 Main heading. It can be used only once in a document, and it represents the most important heading. It is typically displayed in a larger font size than other headings.
- h2 Section heading.
- h3 Subsection heading.
- h4 to h6 Detail headings.

### Paragraphs:

- p The p element represents a paragraph. A paragraph is a block of text that is typically displayed with vertical spacing above and below it, and with the first line indented. The p element can contain inline elements such as a, span, strong, etc., but it cannot contain block-level elements such as div, h1, etc.

### Emphasis and Relevance:

- b The b element represents a span of text to which attention is being drawn for utilitarian purposes without conveying any extra importance and with no implication of an alternate voice or mood, such as key words in a document abstract, product names in a review, actionable words in interactive text-driven software, or an article lede.
- strong The strong element represents strong importance, seriousness, or urgency for its contents. It is typically displayed in bold by user agents. The strong element can be nested, with each level of nesting indicating a greater degree of importance. It is used to indicate a key word
- i The i element represents a span of text in an alternate voice or mood, or otherwise offset from the normal prose in a manner indicating a different quality of text, such as a taxonomic designation, a technical term, an idiomatic phrase from another language, transliteration, a thought, or a ship name in Western texts.,
- em The em element represents stress emphasis of its contents. The em element can be nested, with each level of nesting indicating a greater degree of emphasis.
- del The del element represents a removal from the document. This element is typically rendered by strikethrough text.
- i The ins element represents an addition to the document. This element is typically rendered by underlining the text.

### Quotes:

- Blockquote: The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a footer or cite element, and optionally with in-line changes such as annotations and abbreviations. Its text has to be longer than 40 characters. It is typically displayed visually indented from the left and right margins, and may be rendered in italic.
- q The q element represents a short inline quotation, less than 40 characters. The q element must not contain block-level elements. It is typically rendered with quotation marks around the content.

### Technical Text and Code

- pre The pre element represents a block of preformatted text, in which structure is represented by typographic conventions rather than by elements.
- code The code element represents a fragment of computer code. This could be an XML element name, a file name, a computer program, or any other string that a computer would recognize.

### Abbreviations

- abbr The abbr element represents an abbreviation or acronym, optionally with its expansion. The title attribute may be used to provide an expansion of the abbreviation. The attribute, if specified, must contain an expansion of the abbreviation, and nothing else.

### Highlighted and Clarifying Text

- mark The mark element represents a run of text in one document marked or highlighted for reference purposes, due to its relevance in another context. When used in a quotation or other block of text referred to from the prose, it indicates a highlight that was not originally present but which has been added to bring the reader's attention to a part of the text that might not have been considered important by the original author when the block was originally written, but which is now under previously unexpected scrutiny. When used in the main prose of a document, it indicates a part of the document that has been highlighted due to its likely relevance to the user's current activity.
- small The small element represents side comments such as small print.

### Dates and Times

- Time The time element represents its contents, along with a machine-readable form of those contents in the datetime attribute. The kind of content is limited to various kinds of dates, times, time-zone offsets, and durations, as described below.

## Enlaces

### A Element

If the a element has an href attribute, then it represents a hyperlink (a hypertext anchor) labeled by its contents.

- Attributes
  - href Contains a URL or a URL fragment that the hyperlink points to. A URL fragment is a name preceded by a hash mark (#), which specifies an internal target location (an id of an HTML element) within the current document. URLs are not restricted to Web (HTTP)-based documents, but can use any protocol supported by the browser. For example, file:, ftp:, and mailto: work in most browsers.
  - target Specifies where to display the linked URL. It is a name of, or keyword for, a browsing context: a tab, window, or iframe. The following keywords have special meanings:
    - \_self: Load the URL into the same browsing context as the current one. This is the default behavior.
    - \_blank: Load the URL into a new browsing context. This is usually a tab, but users can configure browsers to use new windows instead.
    - \_parent: Load the URL into the parent browsing context of the current one. If there is no parent, this behaves the same way as \_self.
    - \_top: Load the URL into the top-level browsing context (that is, the "highest" browsing context that is an ancestor of the current one, and has no parent). If there is no parent, this behaves the same way as \_self.
  - rel Specifies the relationship of the target object to the link object. The value is a space-separated list of link types. Give the link a functionality or semantic meaning or purpose.
    - noreferrer: When using target="\_blank", prevents the new page from being able to access the window.opener property and ensures it runs in a separate process. This also prevents the Referer header from being sent to the new page.
    - noopener: When using target="\_blank", prevents the new page from being able to access the window.opener property and ensures it runs in a separate process.
      Note: When using target, consider adding rel="noreferrer" to avoid exploitation of the window.opener API.
      noopener A security measure that prevents the newly opened page from accessing the original page's window.opener object (highly recommended when using target="\_blank").
    - ugc Stands for User Generated Content. It indicates to search engines that the link was created by a user, such as in blog comments, forum posts, or community submissions.
    - nofollow Instructs search engines not to follow the link, preventing any ranking authority or SEO value from being passed to the destination page.
    - sponsored Identifies links that are created as part of advertisements, sponsorships, paid placements, or other commercial agreements.
    - noreferrer nofollow A combination where noreferrer prevents the browser from sending referrer information to the destination site for privacy, and nofollow ensures that no SEO authority or ranking credit is transferred to that site.

**Rules for links:**

- **Forbidden:** Links that only say "Click here" or "Read more".
- **Correct:** The text must describe the destination.
- **Verify that the links work.**

**More attributes of the a element:**

- download This attribute instructs browsers to download a URL instead of navigating to it, so the user will be prompted to save it as a local file. If the attribute has a value, it is used as the pre-filled file name in the Save prompt (the user can still change the file name if they want). There are no restrictions on allowed values, though / and \ are converted to underscores. Most file systems limit some punctuation in file names, and browsers will adjust the suggested name accordingly. If ti has a value, it represents the name of the file to be downloaded.

## Listas

Se usan mucho para menúes de navegación, reels de productos y tajertas de artículos y pies de página

### Clasificación de las Listas:

- Desordenadas (ul)

- Ordenadas (ol)
- Descritivas (dl)
