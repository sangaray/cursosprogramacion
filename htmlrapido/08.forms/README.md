# Forms

A form is a collection of elements use to ask information to an user and send it to a database.

## Form Elements

- `<form>` = The form element represents the collection of form-associated elements.
  **Attributes**
  An attribute defines an action to be performed on a form when a user clicks the submit button.
  - `action` = The URL to send the form data to.
- `<label>` = Form control title.
  **Attributes**
  - `for` = This relates it with a form element.
- `<input>` = Data field.
  **Attributes**
  - `type` = Specifies the type of information the input field accepts.
    **Values**
    - `text` = A single-line text field.
    - `number` = A number field.
    - `password` = A password field with hidden text.
  - `name` = The name attribute specifies the name of the input field. It is used to identify the input field in the server.
  - `maxlegnth` = Specifies the maximum number of characters allowed in the input field.
- `<textarea>` = Multiline data field.
- `<select>` = Selection field among many options.
- `<button>` = Button. It is used to send the form data to the server.

## Aditional Elements

- `<div>` = Generic container.

## Aditiona Attributes

- `id` = The id attribute specifies the id of an input field. It must be unique within the form.
