# Registration Form Project
This is a simple registration form project built using HTML and CSS. The form collects user information, including personal details, account type, profile picture, age, referral source, and a bio. The form also includes terms and conditions that must be accepted by the user.

## Table of Contents
+ `Project Overview`
+ `HTML Markup`
+ `CSS Styles`
+ `Walkthrough`
+ `Project Overview`
+ `Purpose`
The purpose of this project is to create a user-friendly registration form with a visually appealing design. It aims to demonstrate the use of `HTML` for structuring the form elements and CSS for styling.

## Features
User-friendly interface.
Input validation using `HTML` attributes (e.g., required, minlength, pattern).
Stylish design with custom fonts, colors, and layout.

## HTML Markup Sample
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="shortcut icon" href="image/form.ico" type="image/x-icon" />
    <link rel="stylesheet" href="style.css" />
    <title>Registration Form</title>
  </head>
  <body>
    <!-- Form Content Goes Here -->
  </body>
</html>
```
## CSS Styles Sample

```css
@import url(https://fonts.googleapis.com/css?family=Montserrat:100,200,300,regular,500,600,700,800,900,100italic,200italic,300italic,italic,500italic,600italic,700italic,800italic,900italic);
body {
  /* Body Styles */
}

/* Add More CSS Styles Here */

input[type="radio"] {
  font-size: 30px;
  transform: scale(1.4);
  margin-right: 5px;
}
```
## Walkthrough
Form Structure
The `HTML` file contains a registration form with various fields such as first name, last name, email, password, account type, profile picture upload, age input, referral source selection, bio textarea, and terms and conditions checkbox.

## Styling
The `CSS` file provides styling for the entire form. It includes font styling, background color, box-shadow, and specific styling for input elements, checkboxes, and radio buttons.

### Code Snippets
## HTML Form Elements
```html
<!-- Example HTML Markup for First Name -->
<label for="first-name">Enter Your First Name: <input type="text" id="first-name" required name="firstName" /></label>

```
## CSS Styling for Input
    
 ```css
 /* Example CSS Styling for Input */
input,
textarea,
select {
  width: 100%;
  margin-top: 10px;
  /* Add more styling properties here */
}
```
## CSS Styling for Submit Button
```css
    /* Example CSS Styling for Submit Button */
input[type="submit"] {
  display: block;
  width: 60%;
  margin: 0 auto;
  /* Add more styling properties here */
}   
```
## Conclusion
This walkthrough provides an overview of the project, the `HTML markup`, and `CSS styling`. Feel free to explore and modify the code to suit your preferences and requirements.

## Acknowledgments
Special thanks to `FreeCodeCamp` for creating the `Responsive Web Design course`. The knowledge gained from this course greatly contributed to the development of this project.