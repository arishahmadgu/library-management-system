# 📚 Library Management System

This is a simple Library Management System project developed using Java, MySQL, and JDBC. It allows managing books, users, and issuing/returning books in a structured way.

---

## 🛠 Technologies Used
- Java (OOP)
- MySQL (Database)
- JDBC (Java Database Connectivity)
- IntelliJ IDEA (IDE)

---

## 🧱 Project Structure
```
LibraryManagementSystem/
├── src/
│   ├── model/          # Contains entity classes like Book and User
│   ├── dao/            # Handles database operations
│   ├── util/           # Contains DB connection logic
│   └── Main.java       # Entry point of the application
├── sql/
│   └── schema.sql      # SQL script to create and setup the database
└── README.md           # Project instructions and documentation
```

---

## 🗃️ Database Setup
1. Install MySQL and create a new database:
```sql
CREATE DATABASE library_db;
```
2. Run the SQL script in `sql/schema.sql` to create tables.

---

## 🚀 How to Run the Project
1. Clone or download this repository.
2. Open the project in IntelliJ IDEA.
3. Add MySQL JDBC Driver to your project libraries.
4. Configure your MySQL credentials in `DBConnection.java`.
5. Run `Main.java`.

---

## ✨ Features
- Add/View/Delete Books
- Register/View Users
- Issue and Return Books
- Search Books by Title or Author (can be extended)

---

## 📌 Future Enhancements
- Login/Authentication System
- Web-based Frontend (HTML/CSS/JS)
- Email Notifications on Due Date
- Admin Dashboard

---

## 👨‍💻 Author
- Your Name
- [Your GitHub Profile](https://github.com/yourprofile)