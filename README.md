# Django Tweet Project

A simple Twitter/X-like web application built using Django where users can create, edit, delete, and view tweets with image upload functionality and authentication system.

---

# Features

- User Authentication (Login/Register/Logout)
- Create Tweet
- Edit Tweet
- Delete Tweet
- Upload Images with Tweets
- Responsive UI
- Django Admin Panel
- SQLite Database

---

# Tech Stack

- Python
- Django
- HTML
- CSS
- SQLite

---

# Project Structure

```bash
Django_tweet_project/
│
├── chaiheadq/
├── tweet/
├── templates/
├── static/
├── media/
├── manage.py
├── requirements.txt
└── db.sqlite3
```

---

# Installation Process

## 1. Clone the Repository

```bash
git clone https://github.com/sajalsinghal2005/Django_tweet_project.git
```

---

## 2. Move to Project Directory

```bash
cd Django_tweet_project
```

---

## 3. Create Virtual Environment

### Windows

```bash
python -m venv .venv
```

### Linux/Mac

```bash
python3 -m venv .venv
```

---

## 4. Activate Virtual Environment

### Windows

```bash
.venv\Scripts\activate
```

### Linux/Mac

```bash
source .venv/bin/activate
```

---

## 5. Install Required Packages

```bash
pip install -r requirements.txt
```

---

## 6. Apply Migrations

```bash
python manage.py migrate
```

---

## 7. Create Superuser (Optional)

```bash
python manage.py createsuperuser
```

---

## 8. Run Development Server

```bash
python manage.py runserver
```

---

# Open in Browser

```bash
http://127.0.0.1:8000/
```

---

# Admin Panel

```bash
http://127.0.0.1:8000/admin/
```

---

# Future Improvements

- Like & Comment System
- User Profiles
- Search Functionality
- Tailwind CSS Integration
- REST API Integration

---

# Author

Sajal Singhal

---

# GitHub Repository

https://github.com/sajalsinghal2005/Django_tweet_project
