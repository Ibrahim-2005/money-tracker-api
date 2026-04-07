# 💰 Money Tracker API — Full Stack Web Application

A production-ready **expense and income tracking system** built using Flask, designed with a backend-first approach.  
This project demonstrates real-world engineering concepts such as **authentication, user data isolation, relational database design, and scalable backend architecture**.

---

## 🔗 Live Demo  
👉 https://money-tracker-zcps.onrender.com  

---

## 🚀 Key Features

### 🔐 Authentication & Security
- User registration, login, and logout  
- Secure password hashing using Werkzeug  
- Session-based authentication with protected routes  
- Prevents unauthorized access and data leakage  

### 👤 User Data Isolation
- Multi-user support with strict data separation  
- Each user can only access their own transactions  
- Ensures privacy and data integrity  

### ⚡ Backend Architecture
- Designed using **RESTful principles** for modular and scalable backend structure  
- Clean route organization and separation of concerns  
- Easily extendable for future features  

### 💸 Transaction Management
- Add, update, and delete income & expense records  
- Categorized transaction tracking  
- Flexible date handling with default fallbacks  

### 🗂️ Category Management
- Create and manage custom categories  
- Linked to transactions using foreign keys  
- Efficient relational querying  

### 📊 Dashboard Analytics
- Real-time overview of:
  - Total Income  
  - Total Expenses  
  - Net Balance  
- Aggregated calculations for quick financial insights  

### 🛡️ Validation & Error Handling
- Input validation for reliability  
- Handles edge cases (invalid input, session expiry)  
- Graceful error handling  

### 🚀 Deployment
- Deployed using **Gunicorn (WSGI server)**  
- Hosted on **Render**  
- Environment variables used for secure configuration  

---

## 🧠 Tech Stack

| Layer        | Technology |
|-------------|-----------|
| Backend     | Python, Flask |
| Frontend    | HTML, CSS, Jinja2 |
| Database    | SQLite |
| Authentication | Werkzeug Security |
| Deployment  | Gunicorn, Render |
| Version Control | Git, GitHub |

---

## 🗃️ Database Design

The application follows a **normalized relational schema**:

### Users
- `id`, `username`, `password`, `created_at`

### Categories
- `id`, `user_id`, `name`

### Transactions
- `id`, `user_id`, `category_id`, `amount`, `type`, `date`

> Foreign key constraints ensure **data consistency, integrity, and efficient querying**

---

## ⚙️ Local Setup

```bash
git clone https://github.com/Ibrahim-2005/money-tracker-api
cd money-tracker-api
pip install -r requirements.txt
python app.py
```
---
## 👤 Author

**Mohamed Ibrahim**  
Backend Developer | Python & Flask  

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
