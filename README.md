# Password Strength Checker

**Student:** Vishaal S

## Project description

Password Strength Checker is a beginner-friendly cybersecurity project
that evaluates a password against five basic criteria and gives
improvement suggestions.

## Features

-   Checks minimum length (8 characters)
-   Checks uppercase and lowercase letters
-   Checks for digits and special characters
-   Reports Weak, Moderate, or Strong
-   Does not save or send the entered password

## Technology used

-   Python 3
-   Python standard library: `re`, `getpass`
-   Jupyter Notebook (optional)

## Dataset

No dataset is required. The project evaluates a password entered by the
user.

## Setup and run

1.  Install Python 3. No extra packages are required.

2.  Download `Vishaal_S_PasswordStrengthChecker.py`.

3.  Open a terminal in the downloaded folder.

4.  Run:

    ``` bash
    python Vishaal_S_PasswordStrengthChecker.py
    ```

5.  Enter a sample password when prompted. The input is hidden while
    typing.

To use the notebook, open `Vishaal_S_PasswordStrengthChecker.ipynb` in
Jupyter Notebook and run its code cell.

## Example

A password such as `Hello@1234` should be rated **Strong** by these
basic checks.

## Limitations

This is a simple educational checker, not a complete password-security
audit. It does not check leaked-password databases, common-password
lists, or estimated cracking time. Do not use a real personal password
for demonstrations.

## Privacy and safety

The program processes the entered password locally and does not write it
to a file or transmit it over a network.

## GitHub repository

Create a new public or private repository on GitHub, upload the project
files, and paste that repository URL into the submission form.
