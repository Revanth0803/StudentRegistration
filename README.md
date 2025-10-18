# 🎓 Student Registration Form (Java Swing + JDBC)

A **Java Swing-based desktop application** that allows users to register student details, validate inputs, and store information securely in a **MySQL database** using **JDBC**.

---

## 🚀 Features
- 🧍‍♂️ User-friendly GUI built with Java Swing  
- ✅ Input validation for required fields and email format  
- 💾 Database connectivity using MySQL  
- 🔄 Reset and submit functionalities  
- 📋 Success and error message alerts  

---

## 🧰 Tech Stack
| Component | Technology |
|------------|-------------|
| Language | Java |
| GUI Framework | Swing |
| Database | MySQL |
| Connectivity | JDBC |
| IDE | IntelliJ IDEA / Eclipse / NetBeans |

---

## ⚙️ How It Works
1. The user fills in the student registration form.  
2. The application validates all fields (like name and email).  
3. If valid, the data is inserted into the **MySQL database**.  
4. The application shows a success message or an error alert if something goes wrong.  

---

## 🗃️ Database Setup
Use the following SQL commands to create the database and table:

```sql
CREATE DATABASE studentdb;
USE studentdb;

CREATE TABLE students (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(50),
  email VARCHAR(50),
  course VARCHAR(50),
  gender VARCHAR(10)
);
