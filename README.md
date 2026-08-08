# User Registration Form

A modern and responsive **User Registration Form** built using HTML, CSS, and JavaScript.

The form includes real-time validation, success feedback, and a **White Mode / Dark Mode** toggle using the hanging lamp switch.

## Features

- Modern registration form UI
- White Mode and Dark Mode
- Lamp switch for changing themes
- Full name validation
- Email validation
- Password validation
- Minimum 6-character password requirement
- Real-time form validation
- Visual valid/invalid input states
- Create Account button enabled only when all fields are valid
- Success message after successful registration
- Responsive design for mobile devices
- No external libraries required

## Technologies Used

- HTML5
- CSS3
- JavaScript

## Form Fields

### Full Name
The user must enter their full name.

### Email Address
The email must follow a valid email format.

Example:

```text
example@gmail.com

Password

The password must contain at least 6 characters.

Validation

The form provides validation while the user is typing.

Name

If the name is empty:

Please enter your name.

Email

If the email is empty:

Please enter your email.


If the email format is incorrect:

Please enter a valid email address.

Password

If the password contains fewer than 6 characters:

Password must contain at least 6 characters.

Theme Toggle

The lamp at the top-right corner is used to change the theme.

White Mode

White Mode is the default theme when the page loads.

Dark Mode

Click the lamp to switch to Dark Mode.

Click the lamp again to return to White Mode.

Project Structure
user-registration-form/
│
├── index.html
└── README.md

How to Run

Download or clone the project.

Open the project folder.

Open index.html in any modern web browser.

No server or installation is required.

How It Works

JavaScript validates the form fields in real time.

The Create Account button remains disabled until:

Full name is entered
Email address is valid
Password contains at least 6 characters

After successful submission, the following message is displayed:

✓ Account created successfully!


The form is then cleared.

Theme Code

The theme is controlled using the dark class on the <body> element.

lampSwitch.addEventListener("click", function () {
  document.body.classList.toggle("dark");
});

Future Improvements

Possible improvements include:

Confirm password field
Show/hide password button
Password strength indicator
Store registered users in a database
Backend authentication
Login page
Form submission to an API
Remember selected theme using localStorage
License

This project is free to use for learning and personal projects.

:::

You can save this directly as **`README.md`** in the same folder as your `index.html`.
