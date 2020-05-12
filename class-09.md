# Forms and Events

## HTML Chapter 7: Forms

* Form Controls
  * Adding Text:
    * Text input: Used for single line of text such as email addresses and names. `<input type="text" name="username" size="15" maxlength="30" />`
    * Password input: Like a single line text box but it masks the characters entered. `<input type="password" name="password" size="15" maxlength= "30" />`
    * Text area: For longer areas of text. such as messages and comments. 
    `<textarea name="comments" cols="20" rows="4"> Enter your comment</textarea>`
  * Making Choices:
    * Radio buttons: for use when a user must select one of a number of options. `<input type="radio" name="genre" value="rock" />`
    * Checkboxes: When a user can select and unselect multiple options.
    `<input type="checkbox" name="genre" value="rock" />`
    * Drop-down boxes: When a user must pick one of a number of options from a list.
  * Submitting Forms: 
    * Submit buttons: To submit data from your form to another web page.
    * Image buttons: Similar to submit buttons but they allow you to use an image.
  * Uploading files:
    * File upload: allows users to upload files (e.g. images) to a website.

* A user fills in a form and then presses a button to submit the information to the server.
* Form structure: ` <form action="url" method="get"></form>`
* You can group related form controls together inside the `<fieldset>` element.

## HTML Chapter 14: List, Tables & Forms

* The `list-style-type` property allows you to control the shape or style of the bullet point. 
* The `list-style-image` property allows you to use an image to act as a bullet point.
* if you have empty cells in a table, then you can use the `empty-cells` property to specify whether or not their borders should be shown using show, hide, or inherit( this instructs the table cells to obey the controls of the containing table).
* The `border-spacing` property allows you to control the distance between adjacent cells.
* the `cursor` property allows you to control the type of mouse cursor that should be displayed to users.

## JS Chapter 6 Events:

* Events are the browser's way of indicating when something has happened, like when a button is clicked.
* binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen on.
* When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way it is interactive because it has responded to the user.
