
# 📰 CrashBlog - A Django-Powered Blogging Platform

Welcome to **CrashBlog**, a fully-functional blogging web application built with Django! This project is a result of hands-on development aimed at mastering backend web development and deploying production-grade web apps. This repository showcases my ability to build complete web applications from setup to deployment, including database integration, admin panel customization, dynamic routing, and UI design using Bulma CSS.

---

## 🚀 Project Overview

**CrashBlog** includes:

- Fully customizable blog posts
- User-friendly admin interface with filters, search, and auto slugs
- Post categories and comments system
- Search functionality
- Image uploads
- SEO-friendly features: `robots.txt`, `sitemap.xml`
- Deployed on a production server (Ubuntu with Nginx + Gunicorn)

---

## 🧰 Tech Stack

| Technology | Purpose |
|------------|---------|
| Python 3.x | Core language |
| Django 3.2+ | Web framework |
| SQLite3 / PostgreSQL | Database (Dev/Prod) |
| HTML/CSS | Templating |
| Bulma | CSS Framework |
| Font Awesome | Icons |
| Gunicorn | WSGI HTTP server |
| Nginx | Reverse proxy |
| Supervisor | Process manager |
| Git | Version control |
| VS Code | Code editor |

---

## 📸 Features at a Glance

- 🌐 Clean Frontend with Bulma CSS
- 🧑‍💻 Admin Panel Enhancements (search, filters, inline comments)
- 🏷️ Category System
- 💬 Commenting System with Anti-CSRF
- 🗂️ Custom URL Routing using Slugs
- 🖼️ Image Upload for Blog Posts
- 🔍 Post Search with Query Filtering (`Q` objects)
- 🧭 Sitemap and Robots.txt for SEO
- 🔐 Deployed with Nginx + Gunicorn + PostgreSQL on Ubuntu

---

## 📂 Project Structure (Simplified)

```
CrashBlog/
├── blog/               # Blog app (posts, categories, comments)
├── core/               # Core app (homepage, about page)
├── templates/          # HTML Templates
├── media/              # Uploaded media files
├── static/             # Static assets (Bulma, CSS, JS)
├── crashblog/          # Project settings and URLs
├── manage.py           # Django's command-line utility
└── requirements.txt    # Project dependencies
```

---

## 🛠️ Installation & Setup

Clone and set up the project locally:

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/crashblog.git
cd crashblog

# 2. Create a virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Apply migrations and create superuser
python manage.py migrate
python manage.py createsuperuser

# 5. Run the development server
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser.

---

## 💾 Sample Admin Credentials (for testing)

```
Username: admin
Password: admin123 (or your chosen password)
```

---

## 🧪 Key Functionalities to Test

- Add/edit/delete posts via `/admin`
- Add comments to posts from front-end
- Search posts via search bar
- Filter posts by category
- Check `/sitemap.xml` and `/robots.txt`
- Upload images to posts

---

## 🧳 Deployment Instructions

To deploy on Ubuntu:

1. Install dependencies: `nginx`, `gunicorn`, `postgresql`
2. Clone this repo on server
3. Create `.env` and production settings
4. Set up Gunicorn and Supervisor
5. Set up Nginx and point to Gunicorn socket
6. Configure domain name and static/media paths
7. Restart services

_Refer to deployment notes in the tutorial or message me for detailed instructions._

---

## 🔁 Git Workflow

```bash
# Track changes
git status

# Stage changes
git add .

# Commit changes
git commit -m "Describe your changes here"

# Push to GitHub
git push origin main
```

To start a new feature branch:

```bash
git checkout -b feature/your-feature-name
```

---

## 📄 License

This project is open-source and free to use for educational and non-commercial purposes. If you find it useful, consider giving a ⭐️!

---

## 🙋‍♂️ Contact Me

Feel free to reach out if you're hiring, collaborating, or have questions.

- 🌍 Portfolio: [nischalshrestha.info.np](https://www.nischalshrestha.info.np)
- 📫 Email: nischalstha08@gmail.com / hello@nischalshrestha.info.np 
- 💼 LinkedIn: [linkedin.com/in/nischalstha08](https://linkedin.com/in/nischalstha08)

---

## 📸 Screenshots



**Thank you for checking out my project!**
