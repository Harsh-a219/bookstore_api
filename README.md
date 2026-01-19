📚 Bookstore Management System

(Django REST API + JavaScript Frontend)

A full-stack Bookstore Management System built using Django REST Framework for the backend and HTML, CSS, JavaScript for the frontend.
This project demonstrates real-world concepts such as authentication, role-based access control, REST APIs, and frontend-backend integration.

🚀 Features
👤 User Roles

Admin

Add new books

Update book details

Delete books

View all orders

Customer

Register & Login

Browse books

Search books

View available book details

🔐 Authentication & Security

JWT (JSON Web Token) based authentication

Secure login & registration

Role-based permissions (Admin vs Customer)

📦 Book Management

Create, Read, Update, Delete (CRUD) books

Search books by title

Real-time data from backend APIs

🧩 REST API Endpoints
Method	Endpoint	Description
POST	/api/register/	User registration
POST	/api/login/	User login (JWT token)
GET	/api/books/	List all books
POST	/api/books/	Add new book (Admin)
PUT	/api/books/{id}/	Update book (Admin)
DELETE	/api/books/{id}/	Delete book (Admin)
🛠️ Tech Stack
Backend

Python

Django

Django REST Framework

JWT Authentication

SQLite (can be replaced with PostgreSQL / MySQL)

Frontend

HTML5

CSS3

JavaScript (Fetch API)

Tools

VS Code

Git & GitHub

Postman (for API testing)

📂 Project Structure
bookstore_api/
│
├── core/
│   ├── books/
│   │   ├── models.py
│   │   ├── views.py
│   │   ├── serializers.py
│   │   └── urls.py
│   ├── orders/
│   └── settings.py
│
├── manage.py
├── db.sqlite3
└── frontend/
    ├── index.html
    ├── register.html
    ├── books.html
    ├── css/
    └── js/

⚙️ How to Run the Project
1️⃣ Backend Setup
python manage.py makemigrations
python manage.py migrate
python manage.py runserver


Backend will run at:

http://127.0.0.1:8000/

2️⃣ Frontend Setup

Open frontend files using Live Server or browser

Backend APIs are consumed using fetch()

🧪 API Testing

APIs tested using Postman

Supports JSON request/response format

🎯 Learning Outcomes

This project helped me understand:

REST API development

JWT authentication

Django ORM & migrations

Role-based authorization

Frontend–Backend integration

GitHub project management

🌟 Future Enhancements

Payment gateway integration

Book reviews & ratings

Admin dashboard UI

Pagination & filters

Deployment on cloud (AWS / Render)



