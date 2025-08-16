# PHP CRUD Blog with User Authentication

## 📌 Overview
This is a simple **CRUD blog application** built with **PHP and MySQL**.  
It allows users to register, login, and manage their own blog posts.

---

## ✨ Features
- User **Registration & Login** (with hashed passwords).
- **Create, Read, Update, Delete (CRUD)** blog posts.
- Secure SQL queries using `mysqli_real_escape_string`.
- Database schema included (`schema.sql`).
- Clean and simple **UI with CSS**.

---

## 🗄️ Database Schema
Two tables are used:
1. **users** – Stores user accounts.
2. **posts** – Stores blog posts linked to a user.

Schema is provided in `schema.sql`.

---

## 🚀 Setup Instructions
1. Clone or download this project.
2. Import `schema.sql` into MySQL using phpMyAdmin or command line.
3. Update `db.php` with your MySQL credentials:
   ```php
   $servername = "localhost";
   $username = "root";
   $password = "";
   $dbname = "blog_db";
