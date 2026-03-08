# Registration Form with Validation

![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow)
![Status](https://img.shields.io/badge/Project-Active-green)

A simple **web-based registration form** built using **HTML, CSS, and JavaScript** that demonstrates **client-side validation**.  
The form validates user input in real time and ensures that the data entered meets specific criteria before submission.

---

## Project Preview

This project includes a clean UI registration form with validation for:

- Name
- Email
- Password

Error messages are displayed instantly when invalid input is detected.

---

## Features

- Real-time form validation
- Email format validation
- Password strength validation
- Dynamic error messages
- Submit button enabled only when fields are filled
- Simple and clean UI design
- Page refresh after successful submission

---

## Validation Rules

### Name
- Cannot be empty.

### Email
- Must contain exactly **one `@`**
- Must contain **one `.`**
- Cannot end with `.`

---

### Password

Password must contain:

- Minimum **6 characters**
- At least **1 uppercase letter**
- At least **1 number**


---

## How It Works

1. User enters **Name, Email, and Password**.
2. JavaScript listens for `keyup` events.
3. Validation functions check the input fields.
4. Error messages appear if validation fails.
5. Submit button activates when all fields are filled.
6. If all validations pass, the page refreshes after submission.
---
## Future Improvements

- Add **confirm password field**
- Improve email validation using **regular expressions**
- Add **password visibility toggle**
- Store user data using **LocalStorage**
- Connect with a **backend (Node.js / Firebase)**

---

## Author

**Narasimha**

GitHub:  
https://github.com/V-Narasimha

---

⭐ If you found this project useful, consider giving it a **star** on GitHub!
