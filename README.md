# 🗃️ Inventory Management System (Django)

An advanced Inventory Management System built using **Python Django**, allowing admin users to manage products, suppliers, purchases, sales, and inventory transactions with ease. The system is designed with a clean, responsive UI and includes features like authentication, reporting, and dashboard analytics.

---

## 🌐 Deployed Link

👉 [Live Project on PythonAnywhere](https://prabinbehera25.pythonanywhere.com/)

---

## 📌 Features

- ✅ Admin login/logout authentication
- 📦 Add, update, delete products with category support
- 📊 View inventory stock levels with auto-adjusting quantities
- 🧾 Manage purchases and sales entries
- 📈 Generate reports for inventory, suppliers, and sales
- 🧑‍💼 Supplier management
- 🧹 Clean, Bootstrap-based responsive UI
- 🔐 Secured routes using custom middleware

---

## 🧰 Technologies Used

- **Python 3.8+**
- **Django 4.x**
- **SQLite3** (default database, easily switchable to MySQL/PostgreSQL)
- **HTML5 + CSS3 + Bootstrap**
- **JavaScript**
- **PythonAnywhere** (for deployment)

---

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/inventory-management-system.git
   cd inventory-management-system
2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate    # On Windows
   source venv/bin/activate # On Mac/Linux
3. **Install dependencies**
    ```bash
    pip install -r requirements.txt
3. **Apply migrations**
    ```bash
    python manage.py makemigrations
    python manage.py migrate
3. **Create a superuser**
    ```bash
    python manage.py createsuperuser
3. **Run the server**
    ```bash
    python manage.py runserver
3. **Access the app http://127.0.0.1:8000/**

## 📁 Project Structure

├── core/                    # Main project settings  
├── homepage/                # Home and login pages  
├── inventory/               # Inventory item logic  
├── transactions/            # Sales and purchase modules  
├── templates/               # HTML templates  
├── static/                  # CSS, JS, images  
├── db.sqlite3               # Default database  
├── requirements.txt         # Python dependencies  
└── manage.py

## 👨‍💻 Admin Login (after createsuperuser)
    python manage.py createsuperuser
Then access: http://127.0.0.1:8000/admin

## 📸 Screenshots
Coming Soon: Interface screenshots and feature walk-through

