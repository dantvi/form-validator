# Form Validator

The Form Validator project is a responsive web application that validates user input in a sign-up form using HTML, CSS, and JavaScript. Developed as part of the course "JavaScript Web Projects: 20 Projects to Build Your Portfolio" by Zero To Mastery, it ensures secure and user-friendly input handling with real-time feedback and clear validation messages.

## Table of contents

- [Form Validator](#form-validator)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

This project implements a sign-up form with:
- Real-time validation for inputs like name, phone number, email, website URL, and password.
- Password strength enforcement, requiring uppercase, lowercase, numbers, and a minimum of 8 characters.
- Clear error messages to guide users through fixing invalid input.
- Immediate visual feedback, such as color-coded input borders (green for valid, red for invalid).
- Responsive design for seamless usability on desktops and mobile devices.

### Screenshot

![](./screenshot.png)

### Links

- Live Site URL: [DT Code](https://form-validator.dtcode.se/)

### Built with

- HTML5: Semantic form structure and native validation.
- CSS3:
  - Responsive layout with Flexbox.
  - Modern and clean UI design with transitions and CSS variables.
- JavaScript (ES6+):
  - Real-time input validation using the Constraint Validation API.
  - Password matching and validation with regular expressions.
  - Dynamic DOM manipulation for user feedback and interactivity.

### What I learned

In this project, I enhanced my understanding of:
- Using the Constraint Validation API for efficient and user-friendly input validation.
- Writing JavaScript functions for dynamic feedback, such as password strength enforcement and real-time error handling.
- Creating responsive and visually appealing forms with CSS.
- Implementing secure password policies using regex patterns.

Example of password validation logic in JavaScript:

```js
if (password1El.value === password2El.value) {
    passwordsMatch = true;
    password1El.style.borderColor = 'green';
    password2El.style.borderColor = 'green';
} else {
    passwordsMatch = false;
    message.textContent = 'Make sure passwords match.';
    password1El.style.borderColor = 'red';
    password2El.style.borderColor = 'red';
}
```

### Useful resources

- [MDN: Constraint Validation API](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation) - Helped with implementing form validation.
- [MDN: RegExp](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions) - Used for password validation.
- [Google Fonts](https://fonts.google.com/) - Provided the modern and clean typography.

## Author

- GitHub - [@dantvi](https://github.com/dantvi)
- LinkedIn - [@danieltving](https://www.linkedin.com/in/danieltving/)

## Acknowledgments

Special thanks to Zero To Mastery for the inspiration and guidance provided in their course, and to MDN for their comprehensive and detailed documentation.
