# 🌾 AgroBot Project — Task 01  
### **Basic Login System using Flask**

---

## 📘 Overview
A simple Flask web app that allows a user to log in using dummy credentials.  
Demonstrates form handling, flash messages, and route redirection.

---

## 🗂️ Project Structure
app.py

templates/
└─ login.html



---

## ⚙️ Setup

Install Flask and run the app:

pip install flask

python app.py

Then open in your browser:
👉 http://127.0.0.1:5000  or set up own new port
using flask run -p 5001 👉 http://127.0.0.1:5001

🧩 Features

Flask routes for / (login) and /welcome

Dummy credentials:
USERNAME = "admin", PASSWORD = "1234"

Flash messages for success or error

Uses Post/Redirect/Get pattern


💻 Login Page (HTML)

<form method="POST">
  <input type="text" name="username" placeholder="Username" required />
  <input type="password" name="password" placeholder="Password" required />
  <button type="submit">Login</button>
</form>


🧪 Test

✅ Correct Login: admin / 1234 → Redirects to Welcome page

❌ Wrong Login: Shows “Invalid username or password”


