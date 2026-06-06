# Django User Registration and Login System

## Overview

This project is developed using the Django Web Framework to demonstrate user registration and login functionality. The application validates user details using Regular Expressions (Regex) before allowing registration.

## Objectives

* Understand Django project structure.
* Implement user registration.
* Implement user login and authentication.
* Validate user inputs using Regular Expressions.
* Store user information in a database.

## Features

* User Registration
* User Login
* User Authentication
* Form Validation
* Regex-based Validation
* Database Integration using SQLite3

## Technologies Used

* Python
* Django
* HTML
* CSS
* SQLite3
* Regular Expressions (Regex)

## Project Structure

```text
EXP 8 30/
│
├── accounts/
│   ├── migrations/
│   ├── templates/
│   ├── views.py
│   ├── models.py
│   ├── forms.py
│   └── urls.py
│
├── myproject/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── db.sqlite3
├── manage.py
└── README.md
```

## Validation Rules

The application validates user details using Regular Expressions:

### Username Validation

* Only letters, numbers, and underscores allowed.
* Minimum length requirements applied.

### Email Validation

* Must follow standard email format.
* Example: [user@example.com](mailto:user@example.com)

### Password Validation

* Minimum length enforced.
* Must contain letters and numbers.
* Special characters supported.

## Installation and Execution

### Clone Repository

```bash
git clone <repository-url>
cd EXP\ 8\ 30
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install django
```

### Run Migrations

```bash
python manage.py migrate
```

### Start Server

```bash
python manage.py runserver
```

Open browser:

```text
http://127.0.0.1:8000/
```

## Learning Outcomes

* Learned Django project development.
* Learned user authentication mechanisms.
* Implemented form validation using Regex.
* Worked with SQLite database integration.
* Understood Django MVC (MVT) architecture.
