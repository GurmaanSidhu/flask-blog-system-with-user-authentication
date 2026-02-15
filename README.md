# Pageer – Secure Flask Blogging Platform

Pageer is a secure multi-user blogging web application built using Flask.
It allows users to register, login, and create blogs with secure password hashing and session-based authentication.

---

## 🚀 Features

- User registration with encrypted passwords (Bcrypt)
- Secure login and logout (Flask-Login)
- Session-based authentication
- Create and view blogs
- User-specific blog ownership using ForeignKey relationships
- Responsive UI using Bootstrap
- Password visibility toggle
- Clean and consistent authentication pages

---

## 🛠 Tech Stack

- Python
- Flask
- SQLAlchemy (ORM)
- Flask-Login (Authentication)
- Flask-Bcrypt (Password Hashing)
- SQLite (Database)
- Bootstrap (UI Styling)

---

## 🧠 How It Works

- Flask handles routing and HTTP requests.
- SQLAlchemy defines database models and relationships.
- Flask-Login manages user sessions.
- Flask-Bcrypt hashes passwords before storing them.
- SQLite stores user and blog data locally.

Each blog is linked to a specific user using a ForeignKey relationship.

---

## 📂 Project Structure

app.py  
templates/  
  base.html  
  index.html  
  login.html  
  register.html  
  create_blog.html  
static/  
blog.db  

---

## 🔐 Security Implementation

- Passwords are never stored in plain text.
- Passwords are hashed using Bcrypt.
- Protected routes use @login_required.
- Sessions are securely managed with Flask-Login.

---

## ▶️ How to Run Locally

1. Clone the repository:

git clone [https://github.com/yourusername/pageer.git](https://github.com/GurmaanSidhu/flask-blog-system-with-user-authentication.git)

2. Navigate into the folder:

cd pageer

3. Install dependencies:

pip install flask flask-sqlalchemy flask-login flask-bcrypt

4. Run the application:

python app.py

5. Open in browser:

http://127.0.0.1:5000/

---

## 📌 Future Improvements

- Edit and delete blog posts
- Pagination
- Profile page
- Deployment to cloud (Render / Railway / AWS)
- Docker support

---

## 📜 License

This project is created for educational and portfolio purposes.

