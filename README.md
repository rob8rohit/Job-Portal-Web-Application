Job Portal Web Application – Python Full Stack

A full-stack Job Portal web application built using Python (Django & Django REST Framework) that connects Employers and Job Seekers with role-based authentication and real-world job posting and application workflows.

This project is designed to demonstrate backend development, REST API design, authentication, and database management, making it suitable for Python Full Stack / Backend Developer roles.

🚀 Features
👥 User Roles

Admin

Employer

Job Seeker

🔐 Authentication & Authorization

User registration and login

Role-based access control

Secure API endpoints

🏢 Employer Module

Create, update, and delete job postings

View applicants for posted jobs

Manage job status (open/closed)

👨‍💻 Job Seeker Module

Browse and search jobs

Apply for jobs

Upload resume

Track application status

🛠 Admin Module

Manage users

Monitor job postings

Platform overview and control

🧰 Tech Stack

Backend

Python 3.x

Django

Django REST Framework (DRF)

Frontend

HTML

CSS

JavaScript (Vanilla)

Database

SQLite (development)

MySQL / PostgreSQL (production-ready)

Tools

Git & GitHub

REST APIs

📁 Project Structure
job_portal_project/
├── README.md
└── backend/
    ├── manage.py
    ├── jobportal/
    │   ├── settings.py
    │   └── urls.py
    ├── accounts/
    │   ├── models.py
    │   ├── views.py
    │   └── urls.py
    └── jobs/
        ├── models.py
        ├── views.py
        └── urls.py

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/job-portal-django.git
cd job-portal-django/backend

2️⃣ Install dependencies
pip install django djangorestframework

3️⃣ Run migrations
python manage.py makemigrations
python manage.py migrate

4️⃣ Start the server
python manage.py runserver

5️⃣ Access the application
http://127.0.0.1:8000/

📌 API Overview
Method	Endpoint	Description
POST	/api/accounts/register/	User registration
POST	/api/jobs/create/	Create job (Employer)
GET	/api/jobs/	List jobs
📝 Resume Highlights

Developed a full-stack Job Portal using Django and Django REST Framework

Implemented role-based authentication for Admin, Employer, and Job Seeker

Designed and developed RESTful APIs for job posting and applications

Built relational database models for users, jobs, and applications

Followed clean code practices and modular project structure
