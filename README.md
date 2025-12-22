# PRODIGY_CS_03
Password strength assessment tool built using Python to check complexity rules and provide feedback for stronger and more secure passwords.
# 🔐 Password Complexity Checker

A simple and beginner-friendly **Password Complexity Checker** built using **Python**.  
This tool evaluates the strength of a password based on common security criteria and provides helpful feedback to improve password safety.

---

## 📌 Features

- Checks minimum password length
- Detects:
  - Uppercase letters (A–Z)
  - Lowercase letters (a–z)
  - Numbers (0–9)
  - Special characters (!@#$%^&* etc.)
- Classifies password strength as:
  - **Weak**
  - **Medium**
  - **Strong**
- Provides clear suggestions to improve weak passwords

---

## 🧠 How It Works

The password is evaluated using the following rules:

| Criteria | Description |
|--------|------------|
| Length | At least 8 characters |
| Uppercase | Contains at least one uppercase letter |
| Lowercase | Contains at least one lowercase letter |
| Number | Contains at least one digit |
| Special Character | Contains at least one special symbol |

Each satisfied rule increases the strength score.

---

## 🛠️ Technologies Used

- **Python 3**
- **Regular Expressions (re module)**

---
🎯 Project Objective

This project was developed as part of Prodigy Infotech – Task 03 to understand:

Password security fundamentals

Input validation

Basic cybersecurity concepts

Python programming using regular expressions
