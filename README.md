<div align="center">

# 💰 Money Tracker API

> A full-stack Flask web application for managing personal income and expenses with secure authentication, user-specific data isolation, and categorized financial tracking.

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20App-black?logo=flask)
![SQLite](https://img.shields.io/badge/SQLite-blue?logo=sqlite)
![Render](https://img.shields.io/badge/Render-Deployed-success)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red)

</div>

---

## 🌐 Live Demo

🚀 **Live Website:** https://money-tracker-zcps.onrender.com

---

## 🧠 Overview

Money Tracker API is a full-stack personal finance management application built with Flask. It allows users to securely manage their income and expenses, organize transactions using custom categories, and monitor their financial activity through a simple dashboard.

The application focuses on clean backend architecture, relational database design, authentication, and secure user-specific data management.

---

## ✨ Features

### 🔐 Authentication

- User Registration
- Secure Login & Logout
- Password hashing using Werkzeug
- Session-based authentication
- Protected routes

---

### 👤 User Management

- User-specific transactions
- Data isolation between users
- Secure session handling

---

### 💸 Transaction Management

- Add income transactions
- Add expense transactions
- Edit transactions
- Delete transactions
- Manual date selection
- Categorized transaction tracking

---

### 🗂 Category Management

- Create custom categories
- User-owned categories
- Foreign key relationships
- Category-based organization

---

### 📊 Dashboard

- Total Income
- Total Expense
- Current Balance
- Financial summary

---

### 🛡 Validation & Error Handling

- Empty input validation
- Invalid data protection
- Graceful error handling
- Session validation

---

## 🛠 Tech Stack

### Backend

- Python
- Flask
- SQLAlchemy

### Frontend

- HTML5
- CSS3
- Jinja2 Templates

### Database

- SQLite

### Authentication

- Werkzeug Password Hashing
- Flask Sessions

### Deployment

- Gunicorn
- Render

### Version Control

- Git
- GitHub

---

## 🏛 Architecture

```text
Client Browser
       │
       ▼
 Flask Application
       │
       ▼
Authentication
       │
       ▼
SQLAlchemy ORM
       │
       ▼
SQLite Database
```

---

## 🗄 Database Schema

```text
User
 │
 │ 1
 ▼
Category
 │
 │ 1
 ▼
Transaction
```

- A user can create multiple categories.
- Each category can contain multiple transactions.
- Transactions are isolated per authenticated user.

---

## 📁 Project Structure

```text
money-tracker-api/
│
├── 📁 static
│   └── 📁 css
│       └── 🎨 style.css
├── 📁 templates
│   ├── 🌐 base.html
│   ├── 🌐 categories.html
│   ├── 🌐 index.html
│   ├── 🌐 login.html
│   ├── 🌐 register.html
│   └── 🌐 result.html
├── ⚙️ .gitignore
├── 📄 LICENSE
├── 📝 README.md
├── 🐍 app.py
└── 📄 requirements.txt
```

---

## 🚀 Key Features

- User Authentication
- Expense Tracking
- Income Tracking
- Category Management
- Personal Dashboard
- User Data Isolation
- Relational Database Design
- Production Deployment

---

## ⚙ Installation

Clone the repository

```bash
git clone https://github.com/Ibrahim-2005/money-tracker-api.git
```

Navigate into the project

```bash
cd money-tracker-api
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

Open your browser

```text
http://127.0.0.1:5000
```

---

## 🔒 Environment Variables

Create a `.env` file and configure:

```env
SECRET_KEY=your_secret_key
DATABASE_URL=sqlite:///money_tracker.db
```

---

## 💼 Real-World Concepts

This project demonstrates practical backend development concepts including:

- Authentication & Authorization
- CRUD Operations
- Relational Database Modeling
- User-specific Data Security
- Session Management
- Form Validation
- MVC Architecture
- Deployment using Render

---

## 🧠 Key Learnings

- Building authentication systems with Flask
- Designing relational database models
- Managing user sessions securely
- Structuring Flask applications
- Handling forms and validation
- Deploying Python applications to Render

---

## 📈 Future Improvements

- PostgreSQL support
- Charts & financial analytics
- CSV/Excel export
- Monthly reports
- REST API
- Docker support
- Budget planning
- Recurring transactions

---

## ⚠️ Known Limitations

- SQLite is intended for lightweight deployments
- Session-based authentication is not suitable for distributed deployments
- No recurring transaction support
- No data export functionality

---

## 📄 License

This project is protected under an **All Rights Reserved** license.

The source code is publicly available for learning and portfolio purposes only. Copying, modifying, redistributing, or using this project without prior written permission is prohibited.

---

## 👨‍💻 Author

### Mohamed Ibrahim

Backend Developer

**Python • Flask • PostgreSQL**

- GitHub: https://github.com/Ibrahim-2005
- LinkedIn: https://www.linkedin.com/in/mohamed-ibrahim-y/

---

## ⭐ Support

If you found this project interesting, consider giving it a ⭐ on GitHub.