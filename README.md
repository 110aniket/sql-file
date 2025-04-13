# sql-file



# 🚦 Traffic Violation Management System (SQL Project)

This project simulates a basic **Traffic Violation Management System** using SQL. It demonstrates database design, data manipulation, and querying skills by managing records of drivers, vehicles, violations, and fines. The project is designed for practicing SQL concepts such as table creation, foreign key relationships, data insertion, and advanced SQL queries.

---

## 📁 Project Structure

| File Name         | Description                                     |
|------------------|-------------------------------------------------|
| `create_tables.sql` | Contains SQL commands to create all necessary tables (Drivers, Vehicles, Violations) |
| `insert_data.sql`   | Populates the database with sample driver, vehicle, and violation data |
| `queries.sql`       | Includes various SQL queries for retrieving and analyzing traffic data |

---

## 🧱 Database Schema

### 1. **Drivers**
- `driver_id` (Primary Key)
- `name`
- `license_no`
- `age`

### 2. **Vehicles**
- `vehicle_id` (Primary Key)
- `license_plate`
- `driver_id` (Foreign Key)
- `vehicle_type`

### 3. **Violations**
- `violation_id` (Primary Key)
- `vehicle_id` (Foreign Key)
- `violation_type`
- `violation_date`
- `fine_amount`
- `is_paid`

---

## 🔍 Sample Queries

Some of the key SQL queries included:

- Retrieve all traffic violations with driver and vehicle info
- Calculate total unpaid fines per driver
- Get all violations for a specific vehicle
- Use of JOINs, GROUP BY, filtering, and boolean conditions

---

## 💡 Skills Demonstrated

- SQL Table Design and Normalization  
- Primary Key / Foreign Key Relationships  
- Data Insertion and Manipulation  
- Advanced SQL Querying (JOIN, GROUP BY, WHERE, SUM)  
- Real-world scenario modeling

---

## ✅ How to Use

1. Open your SQL environment (MySQL, PostgreSQL, etc.)
2. Run `create_tables.sql` to set up the database schema
3. Execute `insert_data.sql` to populate the tables
4. Use the queries from `queries.sql` to analyze the data

---

## 📌 Author

**Aniket Manna**  
[GitHub Profile](https://github.com/110aniket)

---




.
