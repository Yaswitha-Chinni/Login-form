# 🔐 Login Page Project
<img width="1017" height="911" alt="image" src="https://github.com/user-attachments/assets/802ba0de-0c2b-4ae1-9830-f7d9bccab92d" />

A simple and responsive **Login Page** built using **HTML5**. This project demonstrates form creation, input validation using regular expressions, placeholders, labels, and basic navigation links.

## 📸 Preview

Login form includes:

* Username field
* Password field
* Client-side validation
* Sign In button
* Sign Up link

## 🚀 Features

### Username Validation

* Required field
* Accepts only letters and numbers
* Length between 4 and 20 characters

### Password Validation

* Required field
* Minimum 8 characters
* Must contain:

  * One uppercase letter
  * One lowercase letter
  * One number

### Form Submission

* Uses the `GET` method
* Redirects to the specified action URL after successful validation

## 🛠️ Technologies Used

* HTML5
* Form Validation (Regex Patterns)

## 📂 Project Structure

```text
RealCalcApp/
│
├── HTML/
│   └── Login.html
│
└── README.md
```

## 📋 Code Highlights

### Username Pattern

```html
pattern="[A-Za-z0-9]{4,20}"
```

Allows only alphanumeric characters with a length of 4–20.

### Password Pattern

```html
pattern="(?=.*[a-z])(?=.*[A-Z])(?=.*[0-9]).{8,}"
```

Ensures the password contains:

* At least one lowercase letter
* At least one uppercase letter
* At least one number
* Minimum 8 characters

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repository.git
```

2. Open the project folder.

3. Navigate to:

```text
HTML/Login.html
```

4. Open `Login.html` in any web browser.

## 🎯 Learning Objectives

This project helps beginners understand:

* HTML Forms
* Input Validation
* Regular Expressions
* Form Attributes
* User Authentication UI Design


---

⭐ If you found this project useful, consider giving the repository a star.
