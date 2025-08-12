# Employee Management System (SQL)

This project contains SQL queries for creating and managing an **Employee Management System** database.  
It is designed for beginners and intermediates to learn **database design, CRUD operations, and SQL queries**.

---

## 📂 Database Structure
**Database Name:** `employee_management`  
**Table:** `employees`

| Column Name  | Data Type         | Description |
|--------------|-------------------|-------------|
| emp_id       | INT (PK)          | Employee ID (Auto Increment) |
| first_name   | VARCHAR(50)       | First Name of Employee |
| last_name    | VARCHAR(50)       | Last Name of Employee |
| gender       | ENUM              | Gender (Male, Female, Other) |
| dob          | DATE              | Date of Birth |
| position     | VARCHAR(50)       | Job Position |
| department   | VARCHAR(50)       | Department Name |
| salary       | DECIMAL(10,2)     | Employee Salary |
| hire_date    | DATE              | Date of Hiring |

---

## 🚀 Features
- Create employee database and table
- Insert, update, delete employees
- Search employees by department
- Find highest paid employee
- Count total employees
- Filter employees by hire year

---

## 🛠 How to Run
1. Install **MySQL** on your system.
2. Open **MySQL Command Line** or any SQL client (e.g., MySQL Workbench).
3. Run the `employee_management.sql` script.
4. Execute queries as needed.

---

## 📌 Example Queries
```sql
-- Show all employees
SELECT * FROM employees;

-- Get IT department employees
SELECT * FROM employees WHERE department = 'IT';
