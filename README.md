🍽️ Food Inventory Management System

A full-stack web application built using Django to manage inventory, billing, and staff operations for a food-based business. The system replaces manual processes with a digital solution, improving efficiency, accuracy, and data management.

📌 Features
🔹 Inventory Management
Add, update, and delete products
Track stock in and stock out
Maintain product details (category, quantity, expiry date)
🔹 Stock Monitoring
Identify low-stock items
Track product expiry to reduce wastage
🔹 Billing System
Generate invoices for transactions
Automatically calculate totals
🔹 Invoice Printing
Print invoices directly from the browser using JavaScript
🔹 Report Generation
Export stock data into Excel for analysis
🔹 Role-Based Access Control
Admin, Manager, and Staff roles
Secure access to system features
🔹 User-Friendly Interface
Responsive UI using Tailwind CSS
Simple and easy to use
🛠️ Tech Stack
🔹 Backend
Django (Python)
Django ORM
🔹 Frontend
HTML
CSS
Tailwind CSS
JavaScript
🔹 Database
SQLite
🔹 File Handling
openpyxl (Excel export)
⚙️ Installation & Setup
Clone the repository
git clone https://github.com/your-username/food-inventory-system.git
cd food-inventory-system

Create virtual environment
python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate

Install dependencies
pip install -r requirements.txt

Apply migrations
python manage.py migrate

Run the server
python manage.py runserver

Open browser and go to:
http://127.0.0.1:8000/

🔐 User Roles
Admin → Full access (manage products, users, reports)
Manager → View reports and billing
Staff → Perform stock operations and generate invoices
🧩 System Modules
Inventory Management
Billing & Invoice System
Authentication & Authorization
Reporting System
🧠 Software Engineering Concepts Used
Layered Architecture
Modular Design
MVC (Django MVT Pattern)
Object-Oriented Programming
Role-Based Access Control
Database Abstraction using ORM
DRY (Don’t Repeat Yourself) Principle
🚀 Future Enhancements
PDF invoice generation
Upgrade to PostgreSQL for scalability
Dashboard with analytics and charts
Mobile application integration
Integration with ERP systems

📌 Conclusion

This project demonstrates how software engineering principles can be applied to build a real-world system that improves operational efficiency, reduces manual errors, and provides better inventory control.

👨‍💻 Author
Prutha Sawale
https://github.com/prutha2803/
📄 License
This project is for academic purposes.
