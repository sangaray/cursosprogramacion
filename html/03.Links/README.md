# Links

## a Element

If the a element has an href attribute, then it represents a hyperlink (a hypertext anchor) labeled by its contents.

**Attributes**

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
