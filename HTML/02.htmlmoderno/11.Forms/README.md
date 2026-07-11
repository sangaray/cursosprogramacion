## Forms

Forms stop being just data recolectors and started to be interactive interfaces for users. It is not just capture data but do it with less friction possible.

## Elements

- `<main>` = The main element represents the main content of the body of a document or application. The main content area consists of content that is directly related to or expands upon the central topic of a document or central functionality of an application.
- `<form>`= The form element represents a collection of form-associated elements, some of which can represent editable values that can be submitted to a server for processing.

  **Attributes**
  - `action` = File on the server where the data will be sent. The URI of a program that processes the form information. This value can be overridden by a formaction attribute on a `<button>` or `<input>` element.
  - `method` = Submission method. The HTTP method that the browser uses to submit the form.
    **- Possible values are:**
    `post:` Corresponds to the HTTP POST method ; form data are included in the body of the form and sent to the server.
    `get:` Corresponds to the HTTP GET method; form data are appended to the action attribute URI with a '?' as separator, and the resulting URI is sent to the server. Use this method when the form has no side-effects and contains only ASCII characters.
    `dialog:` Use when the form is inside a `<dialog>` element to close the dialog when submitted.
    This value can be overridden by a formmethod attribute on a `<button>` or `<input>` element.
  - `autocomplete` = Indicates whether input elements can by default have their values automatically completed by the browser. This setting can be overridden by an autocomplete attribute on an element belonging to the form.
    **Possible values are:**
    - `off:` The user must explicitly enter a value into each field for every use, or the document provides its own auto-completion method; the browser does not automatically complete entries.
    - `on:` The browser can automatically complete values based on values that the user has previously entered in the form. For most modern browsers (including Firefox 38+, Google Chrome 34+, IE 11+) setting the autocomplete attribute will not prevent a browser's password manager from asking the user if they want to store login fields (username and password), if the user permits the storage the browser will autofill the login the next time the user visits the page. See The autocomplete attribute and login fields. Note: If you set autocomplete to off in a form because the document provides its own auto-completion, then you should also set autocomplete to off for each of the form's input elements that the document can auto-complete. For details, see the note regarding Google Chrome in the Browser Compatibility chart.
    - `username:` The browser can automatically complete values based on values that the user has previously entered in the form. This is the default setting for the autocomplete attribute.
    - `new-password:` The browser can automatically complete values based on values that the user has previously entered in the form. This is the default setting for the autocomplete attribute.

- `<fieldset>`= The fieldset element represents a set of form controls optionally grouped under a common name.
- `<legend>` = The legend element represents a caption for the rest of the contents of the legend element's parent fieldset element, if any.
- `<label>` = The label element represents a caption in a user interface. The caption can be associated with a specific form control, known as the label element's labeled control, either using the for attribute, or by putting the form control inside the label element itself.
  **Attributes**
  - `for` = The id of a labelable form-related element in the same document as the <label> element. The first element in the document with an id matching the value of the for attribute is the labeled control for this label element, if it is a labelable element. If it is not labelable then the for attribute has no effect. If there are other elements which also match the id value, later in the document, they are not considered.
    Note: A `<label>` element can have both a for attribute and a contained control element, as long as the for attribute points to the contained control element.
- `<input>` = The input element represents a typed data field, usually with a form control to allow the user to edit the data.
  **Attributes**
  - `type` = The type attribute specifies the type of input control to use.
    **Possible values are:**
    - `text`= A single-line text field
    - `email` = An email field
    - `tell` = A phone number field
    - `date` = A date field
    - `password` = A password field
    - `checkbox` = A checkbox field

  - `name` = The name attribute specifies the name of an input field. It must be unique within the form.
  - `id` = The id attribute specifies the id of an input field. It must be unique within the form. it must be the same as the for attribute of the label element to be connected with the input field.
  - `required` = The required attribute specifies that the user must fill in the field before submitting the form.
  - `placeholder` = The placeholder attribute specifies a short hint that describes the expected value of an input field.
  - `pattern` = The pattern attribute specifies a regular expression that the input field must match. Se usan regex.
