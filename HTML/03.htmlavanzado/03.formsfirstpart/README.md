# Forms First Part

## Form

It is a way for the user to interact with the web server and send data.

## Form Elements

- `<form>` = The form element represents a collection of form-associated elements, some of which can represent editable values that can be submitted to a server for processing.

  **Attributes**
  - `action` = The URL to send the form data to.
  - `method` = The HTTP method to use when submitting the form.

    **Values**
    - `get` = The form data is appended to the URL as a query string.
    - `post` = The form data is included in the body of the request and it is not visible to the user.

  - `target` = Specifies where to display the response that is received after submitting the form.

    **Values**
    - `_blank` = Opens the response in a new window or tab.
    - `_self` = Opens the response in the same frame as it was submitted.
    - `_parent` = Opens the response in the parent frame.
    - `_top` = Opens the response in the full body of the window.

- `<label>` = The label is an element that represents a caption for an item in a user interface.

  **Attributes**
  - `for` = This relates it with other form element.

- `<input>` = The input element allows the user to input data.

  **Attributes**
  - `type` = Specifies the type of information the input field accepts.

    **Values**
    - `text` = A single-line text field.
    - `radio`= A radio button, it is used to make single selection in a group of options

  - `name` = Specifies a name of for the input field. It is used to identify the input field in the server.

    **Notas**
    - When used with radio buttons, in order to be able to select only one option, the `name` attribute must be the same for all the radio buttons.

  - `id` = Gives the input element a unique identifier that can be used to reference the element.
  - `value` = Sets the initial value of the input field. Also should be use with radio buttons to allows the user to select only one option.
