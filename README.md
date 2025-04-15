
# 📊 Jihad Al-Binaa Organization – Database System Project

A complete relational database system built for the Jihad Al-Binaa Organization, aimed at managing projects, employees, volunteers, tools, activities, donors, and financial transactions.

---

## 📘 Project Overview

This project was developed to digitally model and manage the operations and projects of the **Jihad Al-Binaa Organization**, which supports community development in education, agriculture, construction, health, environment, and more.

The database includes:
- A relational model for multiple entities (projects, employees, departments, donors, etc.)
- Real-world queries, views, stored procedures, and triggers
- Role-based user permissions for data management

---

## 📐 ER Diagram & Relational Model

The system models entities like:
- Employee
- Volunteer
- Department
- Project
- Donor
- Payment
- Tools
- Location, Region, and Activities

Key relationships include:
- Projects assigned to departments and categories
- Employees and volunteers assigned to activities
- Tools required for activities
- Donors linked to payments

---

## 🧱 Database Implementation

Database Name: `JihadAlBinaa`

### Main Tables:
- `Employee`, `Volunteer`, `Department`, `Project`, `Donor`, `Payment`, `Tools`, `Location`, `Region`
- Many-to-many and one-to-many relationships implemented via foreign keys

### Sample SQL Tasks:
- Table creation with constraints
- Inserting data (INSERT)
- Updating and deleting data (UPDATE, DELETE)
- Complex queries using JOINs and subqueries

---

## 🧠 SQL Features

### ✅ Queries:
- JOIN queries across multiple tables
- Subqueries for filtering by conditions
- Aggregate functions (SUM, AVG)
- Conditional logic in SELECT statements

### 👁️ Views:
- `projectsActivityDetails` — tools used per project
- `paymentsOfProjectt` — total payments per project
- `donorPayment` — donor contributions with project names
- `regionOfActivity` — region of each activity

### ⚙️ Procedures:
- Get average salary by major
- Count achievements by department
- Check project start eligibility based on payments
- Increment achievements for departments

### 🚨 Triggers:
- Prevent insert if employee is under 18
- Insert reminders if employee blood type is AB
- Prevent salary decrease
- Log salary changes
- Archive deleted activities

---

## 👥 Users and Permissions

### Sample Users:
- `user_1` – Full access to all databases
- `user_2` – Limited access to activities and tools
- `user_8` – Full access to employee, department, and achievements
- `user_12` – Access to region table only
- `user_10` – Read-only access

---

## 🧪 Testing & Verification

- Insert, update, and delete operations tested on all main entities
- Views tested with SELECT statements
- Triggers tested on salary, age, and deletion actions
- Stored procedures executed and validated with parameters

---

## 💻 Technologies Used

- **SQL (MySQL syntax)**
- **ER modeling**
- **Views, Procedures, Triggers**
- **User Access Control**

---


## 👩‍💻 Author

**Fatima Hammoud**  
Department of Computer Science  
Al Maaref University  
Database Systems Lab – 2024



