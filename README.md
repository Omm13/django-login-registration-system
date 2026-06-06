# Django Login & Registration System

## Overview

A Django-based User Authentication System that provides secure user registration and login functionality with form validation and database integration. This project demonstrates the implementation of authentication workflows, user input validation, and backend web development using the Django framework.

The application allows users to create accounts, log in securely, and access protected features while maintaining data integrity through validation mechanisms.

---

## Objectives

* Understand Django project structure and workflow.
* Implement user registration and login functionality.
* Perform server-side form validation.
* Manage user data using SQLite database.
* Learn Django's MVT (Model-View-Template) architecture.
* Handle user authentication securely.

---

## Features

* User Registration System
* User Login Authentication
* Form Validation
* Regex-Based Input Validation
* Error Handling and User Feedback
* SQLite Database Integration
* Django MVT Architecture
* Secure User Data Management

---

## Technologies Used

| Technology | Purpose              |
| ---------- | -------------------- |
| Python     | Programming Language |
| Django     | Backend Framework    |
| SQLite     | Database             |
| HTML       | Structure            |
| CSS        | Styling              |
| Regex      | Input Validation     |

---

## Project Structure

```text
project/
│
├── app/
│   ├── migrations/
│   ├── templates/
│   ├── static/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│
├── project/
│   ├── settings.py
│   ├── urls.py
│
├── db.sqlite3
├── manage.py
```

---

## Validation Rules

The project includes validation checks such as:

* Username validation
* Password strength validation
* Email format validation
* Empty field prevention
* Duplicate user prevention

Regex patterns are used to enforce specific input requirements and improve data consistency.

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/django-login-registration-system.git
```

### 2. Navigate to the Project Folder

```bash
cd django-login-registration-system
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run Migrations

```bash
python manage.py migrate
```

### 7. Start Development Server

```bash
python manage.py runserver
```

### 8. Open Browser

```text
http://127.0.0.1:8000/
```

---

## Skills Demonstrated

* Django Framework
* User Authentication
* Form Handling
* Regular Expressions (Regex)
* SQLite Database Management
* Backend Development
* MVT Architecture
* Input Validation
* Session Management
* CRUD Fundamentals

---

## Learning Outcomes

Through this project, I learned:

* Django project architecture
* Backend web development fundamentals
* Authentication workflows
* Form validation techniques
* Database integration using SQLite
* URL routing and view handling
* Template rendering in Django
* Secure user management practices

---

## Future Enhancements

* Password Reset Functionality
* Email Verification
* User Profile Management
* Role-Based Authentication
* PostgreSQL Integration
* OAuth Login (Google/GitHub)
* User Activity Dashboard
* Improved UI/UX Design

---

## Author

**Omm Miriyala**
GitHub: https://github.com/Omm13
