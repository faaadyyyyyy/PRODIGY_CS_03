# Password Strength Assessor

A Python tool to assess the strength of a password based on various criteria including length, presence of uppercase and lowercase letters, numbers, and special characters. The tool provides feedback on the password's strength and suggests improvements.

## Features

- **Length Check**: Ensures the password is at least 8 characters long.
- **Uppercase Check**: Requires at least one uppercase letter.
- **Lowercase Check**: Requires at least one lowercase letter.
- **Digit Check**: Requires at least one numerical digit.
- **Special Character Check**: Requires at least one special character (e.g., `!@#$%^&*()`).

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/Fiiaaad/PRODIGY_CS_03.git
    ```

2. Navigate to the project directory:

    ```bash
    cd password-strength-assessor
    ```

3. No additional libraries are required as this script uses only built-in Python libraries.

## Usage

1. Run the script:

    ```bash
    python password_strength_assessor.py
    ```

2. Enter a password when prompted.

3. The tool will assess the password and provide feedback on its strength, along with suggestions for improvement if necessary.

### Example

```bash
$ python password_strength_assessor.py
Enter your password: MyP@ssw0rd!
Password Strength: Strong password!

$ python password_strength_assessor.py
Enter your password: short
Password Strength: Weak password.
Suggestions for improvement:
- Password should be at least 8 characters long.
- Password should contain at least one uppercase letter.
- Password should contain at least one special character.
