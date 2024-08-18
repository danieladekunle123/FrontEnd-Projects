# Registration Form

This project consists of a simple HTML registration form styled with CSS. It allows users to enter their personal information to register for an account. The form supports input validation for essential fields.

## Features

- **Form Validation**: Ensures all required fields are filled out before submission.
- **Responsive Design**: Adapts to different screen sizes to enhance usability on multiple devices.
- **Custom Styling**: Uses CSS to provide a visually appealing and user-friendly interface.

## Form Details

The form includes several types of inputs and validation mechanisms:
- **Text Inputs**: For entering first name, last name, and email.
- **Password Input**: For creating a new password, with a pattern requirement for validation.
- **Radio Buttons**: For selecting an account type.
- **File Input**: For uploading a profile picture.
- **Number Input**: For entering age, with specified minimum and maximum values.
- **Dropdown**: For selecting how the user heard about the website.
- **Text Area**: For writing a short bio.
- **Checkbox**: For agreeing to the terms and conditions.

## HTML Structure

The HTML file is structured with various sections:
- **Head**: Contains metadata and links to the CSS stylesheet.
- **Body**: Houses the main content including the form with various fieldsets for categorizing input fields.

### Code Snippet

Here's a snippet of the form element:

```html
<form>
  <fieldset>
    <label for="first-name">Enter Your First Name: <input id="first-name" type="text" required /></label>
    ...
  </fieldset>
  <input type="submit" value="Submit" />
</form>
```

## CSS Styling

The CSS for this form provides a dark theme with contrasting text colors for readability. It includes styles for the body background, text alignment, form padding, input styles, and responsive widths.

## Conclusion

This registration form is designed to be straightforward and functional, suitable for websites requiring user registration. The responsive design ensures it works well on both desktop and mobile devices.
