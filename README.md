# 🌾 AgroBot Project — Task 01  
### **Basic Login System using Flask**

---

## 📘 Overview
A simple Flask web app that allows a user to log in using dummy credentials.  
Demonstrates form handling, flash messages, and route redirection.

---

## 🗂️ Project Structure

app.py

login.html



---

## ⚙️ Setup

Install Flask and run the app:

pip install flask

python app.py

Then open in your browser:
👉 http://127.0.0.1:5000  or set up own new port
using flask run -p 5001 👉 http://127.0.0.1:5001

---


<img width="1899" height="995" alt="output" src="https://github.com/user-attachments/assets/6b7320fa-b1b2-4cc4-b0f7-f8d1f82f09ba" />


🧩 Features

Flask routes for / (login) and /welcome

Dummy credentials:
USERNAME = "admin", PASSWORD = "1234"

Flash messages for success or error

Uses Post/Redirect/Get pattern

---

🧪 Test

✅ Correct Login: admin / 1234 → Redirects to Welcome page

❌ Wrong Login: Shows “Invalid username or password”


