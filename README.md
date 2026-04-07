# 🎓 Student Management System (JDBC Project)

## 💡 About the Project

This is a simple **Student Management System** built using **Core Java and JDBC**.
I created this project to understand how Java connects with a database and how real-world applications handle data.

The application runs on the console and allows users to manage student records easily.

---

## 🚀 What this project can do

* Add new student details
* View all students stored in the database
* Update student percentage using ID and email
* Delete a student record by ID

---

## 🛠️ Technologies I used

* Java
* JDBC
* MySQL
* Eclipse IDE

---

## 📂 Project Structure

I followed a layered approach to keep the code clean and organized:

* **DTO (Student.java)** → stores student data
* **DAO (StudentDAO.java)** → handles database operations
* **Controller (StudentMain & StudentService)** → manages user input and logic

---

## 🗄️ Database Setup

**Database Name:** `advance_java`
**Table Name:** `student_details`

```sql
CREATE TABLE student_details (
    student_id INT PRIMARY KEY,
    student_name VARCHAR(50),
    student_emailid VARCHAR(50),
    student_password VARCHAR(50),
    student_mobileno BIGINT,
    student_percentage DOUBLE,
    student_gender VARCHAR(10),
    student_stream VARCHAR(20),
    student_degree VARCHAR(20),
    student_address VARCHAR(100)
);
```

---

## ▶️ How to Run

1. Create the database and table in MySQL
2. Open the project in Eclipse
3. Check your DB username & password in the code
4. Run `StudentMain.java`
5. Use the menu to perform operations

---

## 🧠 What I learned

* How to connect Java with MySQL using JDBC
* How CRUD operations work in real projects
* Importance of project structure (DAO, DTO, Controller)
* Writing SQL queries inside Java

---

## 🔮 Future Improvements

* Add login functionality
* Add input validation
* Convert this into a web application using Servlets & JSP

---
