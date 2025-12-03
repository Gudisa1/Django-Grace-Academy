
# 🧩 Django Full-Stack Project – Student Management System

> A **full-stack Django web application** built step-by-step as part of a comprehensive **project-based course**. Learn backend development, database design, templates, forms, authentication, admin management, and deployment.

---

## 🎯 Project Overview

The **Student Management System** project covers:

* Creating a Django project and app from scratch
* Designing **models** with Django ORM
* Managing data with the **Django admin panel**
* Building dynamic **views and templates**
* Handling **forms and user input validation**
* Implementing **authentication and authorization**
* Deploying a production-ready web app

**Outcome:** A fully functional, deployed web application suitable for portfolios or job interviews.

---

## 📂 Project Structure

```text
student-management-system/
│
├─ core/                  # Django project folder
│   ├─ settings.py
│   ├─ urls.py
│   ├─ wsgi.py
│
├─ students/              # Django app
│   ├─ models.py
│   ├─ views.py
│   ├─ forms.py
│   ├─ urls.py
│   ├─ templates/
│   │   └─ students/
│   │       ├─ home.html
│   │       ├─ add_student.html
│   │       ├─ edit_student.html
│   │       └─ login.html
│   └─ static/
│       └─ css/
│
├─ manage.py
├─ requirements.txt
├─ README.md
└─ LICENSE
```

---

## 🛠 Tools & Technologies

* **Backend:** Python, Django
* **Database:** SQLite (default) / PostgreSQL (optional)
* **Frontend:** HTML, CSS, Bootstrap
* **Deployment:** Render, Railway, PythonAnywhere
* **IDE:** VS Code / PyCharm

---

## 🚀 Features

* ✅ CRUD functionality for students
* ✅ Admin panel with search, filters, and ordering
* ✅ User authentication: signup, login, logout
* ✅ Form validation and CSRF protection
* ✅ Dynamic templates with Bootstrap styling
* ✅ Production-ready deployment

---

## 🎬 Course-Aligned Video Guide

This project follows a **30-video course structure**:

**Phase 1: Django Basics & Setup**

* What is Django? (Backend Explained)
* Install Python & VS Code
* Virtual Environment & Django Installation
* Create Project & Run Server

**Phase 2: Django App Architecture**

* Create First App
* First View & HTTP Response

**Phase 3: Database & Models**

* Database & ORM Basics
* Build Student Model
* Migrations & Database Setup
* Django Shell & Sample Records

**Phase 4: Django Admin (Immediate Feedback)**

* Admin Setup & Superuser
* Register Models & Customize Admin Panel
* Full CRUD in Admin

**Phase 5: Views & Templates**

* Django Templates Explained
* Display Students in HTML
* Add Bootstrap Styling

**Phase 6: URL Routing & Navigation**

* URL Routing Explained
* Dynamic URLs & Path Parameters

**Phase 7: Forms & User Input**

* Django Forms & POST Requests
* Build Add Student Form
* Form Validation & Save to Database
* Update & Delete Using Forms

**Phase 8: Authentication & Authorization**

* Auth vs Authorization
* Build Signup System
* Build Login System
* Protect Pages with login_required
* Logout & User Roles

**Phase 9: Deployment & Production**

* Production Settings Explained
* Deploy to Render / Railway / PythonAnywhere
* Final Project Demo & Portfolio Guide

---

## 📝 Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/student-management-system.git
cd student-management-system
```

2. **Create virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run migrations**

```bash
python manage.py makemigrations
python manage.py migrate
```

5. **Create superuser**

```bash
python manage.py createsuperuser
```

6. **Run server**

```bash
python manage.py runserver
```

7. **Open browser:** `http://127.0.0.1:8000`

---

## 📌 Key Pages

* **Home Page:** List all students
* **Add Student:** Add a new student
* **Edit Student:** Update student details
* **Delete Student:** Remove student
* **Admin Panel:** Manage students
* **Login / Signup:** Authentication system

---

## 🌟 Deployment

Steps for live deployment:

1. Set `DEBUG = False` in `settings.py`
2. Configure `ALLOWED_HOSTS`
3. Collect static files:

```bash
python manage.py collectstatic
```

4. Deploy to Render / Railway / PythonAnywhere
5. Set environment variables for production

---

## 💡 Learning Outcomes

* Django project structure & apps
* Models & database migrations
* Views & templates rendering dynamic content
* Form handling & validation
* Admin panel management
* Authentication & authorization
* Deployment of production-ready web app

---

## 📖 References

* [Django Documentation](https://docs.djangoproject.com/)
* [Bootstrap Documentation](https://getbootstrap.com/docs/)

---

## 📝 License

MIT License – free to reuse and modify for learning or portfolio purposes.

---

