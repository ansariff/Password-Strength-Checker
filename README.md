# Password Strength Checker 🔒

This is a simple yet effective GUI-based application built with Python using the `customtkinter` library to check the strength of passwords. The app evaluates whether a password meets specific criteria and provides immediate feedback on its strength (Strong or Weak).

---

## Features ✨
- **Interactive User Interface**: Built with `customtkinter` for an enhanced modern look.
- **Real-Time Feedback**: Checks password strength immediately upon input.
- **Criteria for Strong Passwords**:
  - At least 8 characters long
  - Contains at least one uppercase letter
  - Contains at least one lowercase letter
  - Contains at least one digit
  - Includes at least one special character (`!@#$%^&*()_+-=~\`{}[]:";<>,.?/`)
- Displays "Strong Password" or "Weak Password" with color-coded results:
  - Green for strong passwords
  - Red for weak passwords
- Alerts the user if no password is entered.

---

## Installation 🛠️

### Prerequisites
- Python 3.9 or later installed.
- The following Python libraries:
  - `customtkinter`
  - `tkinter`
  - `re`

### How to Install
1. Clone or download this repository:
   ```bash
   git clone https://github.com/yourusername/password-strength-checker.git
   cd password-strength-checker
