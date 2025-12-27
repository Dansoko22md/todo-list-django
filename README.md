# Todo List Django

A simple todo list application built with Django. Features full CRUD operations to learn Django basics including models, views, templates, and forms.

## Features
- Add, edit, delete, and mark tasks as completed
- Simple and clean interface
- Learn Django project structure and basics

## Installation

1. **Clone or download this repository**
2. **Create a virtual environment (optional but recommended):**
   
	Windows:
	```sh
	python -m venv .venv
	.venv\Scripts\activate
	```
   
3. **Install dependencies:**
	```sh
	pip install django
	```

4. **Apply migrations:**
	```sh
	python manage.py migrate
	```

5. **Run the development server:**
	```sh
	python manage.py runserver
	```

6. **Open your browser and go to:**
   
	http://127.0.0.1:8000/

## Usage
- Add, edit, or delete tasks from the main page.
- Access the Django admin at http://127.0.0.1:8000/admin/ (create a superuser with `python manage.py createsuperuser` if needed).

## Project Structure
- `todo/` - Main app with models, views, forms, and templates
- `config/` - Project settings and URLs

## Learning Resources
- [Django Documentation](https://docs.djangoproject.com/en/stable/)

---

*Project for learning purposes.*
