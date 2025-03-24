# Supermart Inventory Management System

## 📌 Overview
The **Supermarket Inventory Management System** is a web-based application designed to streamline inventory tracking and order management for supermarkets and retail stores. This system ensures efficient stock monitoring, order logging, and database integrity through the use of triggers and stored procedures.

## 🚀 Features
- **Inventory Management**: Add, update, and delete product details.
- **Order Processing**: Place and track customer orders.
- **Order Logs**: Maintain records of all past transactions.
- **Automatic Stock Updates**: Reduces stock automatically when an order is placed.
- **Category Management**: Add and manage product categories.
- **Database-Driven**: Uses MySQL with triggers and stored procedures for optimized performance.

## 🛠 Technologies Used
- **Frontend**: HTML, CSS
- **Backend**: PHP
- **Database**: MySQL
- **Server**: Apache (via XAMPP)

## 📥 Installation
### Prerequisites
- XAMPP installed (or any PHP and MySQL-supported server environment).

### Steps to Run the Project
1. Clone or download the repository.
2. Move the project folder to the XAMPP `htdocs` directory.
3. Start **Apache** and **MySQL** from the XAMPP Control Panel.
4. Open `phpMyAdmin` and create a database named `inventory`.
5. Import the provided SQL file (if applicable) or let the script auto-create tables.
6. Open a browser and navigate to `http://localhost/supermarket-inventory`.

## 🗄 Database Structure
The system uses the following tables:
1. **categories** – Stores product categories.
2. **products** – Stores product details.
3. **orders** – Tracks customer orders.
4. **order_logs** – Maintains order history.

## 🔄 Functional Flow
1. Admin adds product categories and products.
2. When an order is placed, the stock quantity is updated automatically.
3. Order logs are generated using a database trigger.
4. Stored procedures allow fetching product details efficiently.

## 📈 Future Enhancements
- User authentication and role-based access control.
- Sales analytics and reporting.
- Barcode scanning for quick product entry.

## 📜 License
This project is open-source and free to use for educational purposes.


