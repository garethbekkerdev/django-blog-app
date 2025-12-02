# Django Blog App

A simple blog web‑application built with Django — educational / portfolio project.

## Overview

This project is a basic blog platform built using Django.
It supports:

* Creating, viewing, updating, and deleting blog posts (CRUD)
* User authentication (login/signup)
* Viewing posts by individual users

It’s a portfolio/demo project to showcase what I’ve learned about Python, Django, and web application basics.

## 🛠️ Tech Stack

* Python 3.x
* Django (backend framework)
* SQLite (default DB for development)
* HTML / CSS (basic frontend templates)
* (Optional) Additional dependencies: image support via Pillow, styling with django-crispy-forms — as listed in `requirements.txt`

## 🚀 Getting Started / Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/garethbekkerdev/django-blog-app.git
   cd django-blog-app/D2Proj    # or the path to your project root
   ```

2. (Recommended) Create and activate a virtual environment:

   ```bash
   python -m venv env
   # Windows
   env\Scripts\activate
   # macOS / Linux
   source env/bin/activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

5. (Optional) Create a superuser (for admin access):

   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:

   ```bash
   python manage.py runserver
   ```

7. Open a browser and go to:

   ```
   http://127.0.0.1:8000/
   ```

You should see the blog homepage.

## 📖 Usage / Features

* View all blog posts (homepage)
* Create a new post (requires login)
* Edit / delete existing posts (only allowed for post author)
* View individual post detail pages
* View posts by a specific user (via “user/<username>” route)
* User login / logout / signup

## 🧰 Project Structure (at glance)

```
D2Proj/                   ← project root
├── manage.py             ← Django management script
├── requirements.txt      ← Python dependencies
├── .gitignore            ← ignored files/folders (venv, caches, etc.)
├── README.md             ← this file
├── …                     ← Django project and app folders, templates, static files, etc.
```

## 📄 License / Usage

Feel free to use this code for learning, building, or extending projects. No guarantee given — use at your own risk.

---

**Created by Gareth Bekker**
Contact: garethbekkerdev@gmail.com
