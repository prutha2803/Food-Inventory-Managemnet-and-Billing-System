# 🍽️ Food Inventory Management System

A full-stack web application built using **Django** to manage inventory, billing, and staff operations for a food-based business. The system replaces manual processes with a digital solution, improving efficiency, accuracy, and data management.

---

## 📌 Features

- Inventory Management: Add, update, and delete products, track stock in/out, and maintain product details (category, quantity, expiry date)
- Stock Monitoring: Identify low-stock items and track expiry dates to reduce wastage
- Billing System: Generate invoices and automatically calculate totals
- Invoice Printing: Print invoices directly from the browser using JavaScript
- Report Generation: Export stock data into Excel for analysis
- Role-Based Access Control: Admin, Manager, and Staff roles with restricted permissions
- User-Friendly Interface: Responsive UI using Tailwind CSS

---

## 🛠️ Tech Stack

**Backend:**
- Django (Python)
- Django ORM

**Frontend:**
- HTML
- CSS
- Tailwind CSS
- JavaScript

**Database:**
- SQLite

**File Handling:**
- openpyxl (Excel export)

---

## ⚙️ Installation & Setup

1. Clone the repository
git clone https://github.com/your-username/food-inventory-system.git
cd food-inventory-system


2. Create virtual environment
python -m venv env
source env/bin/activate # On Windows: env\Scripts\activate


3. Install dependencies
pip install -r requirements.txt


4. Apply migrations
python manage.py migrate


5. Run the server
python manage.py runserver


6. Open browser:
http://127.0.0.1:8000/


---

## 🔐 User Roles

- Admin: Full access (manage products, users, reports)
- Manager: Access to reports and billing
- Staff: Perform stock operations and generate invoices

---

## 🧩 System Modules

- Inventory Management
- Billing & Invoice System
- Authentication & Authorization
- Reporting System

---

## 🧠 Software Engineering Concepts Used

- Layered Architecture
- Modular Design
- MVC (Django MVT Pattern)
- Object-Oriented Programming (OOP)
- Role-Based Access Control
- Database Abstraction using ORM
- DRY (Don’t Repeat Yourself) Principle

---

## 🚀 Future Enhancements

- PDF invoice generation
- Upgrade to PostgreSQL for scalability
- Dashboard with charts and analytics
- Mobile application support
- Integration with ERP/accounting systems


---

## 📌 Conclusion

This project demonstrates how software engineering principles can be applied to build a real-world inventory system that improves efficiency, reduces errors, and enhances operational control.

---

## 👨‍💻 Author

Prutha Sawale
GitHub: (https://github.com/prutha2803/)

---

## 📄 License

This project is for academic purposes.
