# Course Management System

A desktop application developed in Java Swing with MySQL database integration to manage students, courses, and enrollments.



## Features

- View and manage student details
- View and manage courses
- Enroll students in courses
- Display student list with course enrollment details

---

## Technologies Used

- Java SE (Swing for GUI)
- MySQL (Database)
- JDBC (Java Database Connectivity)
- NetBeans IDE (Recommended)

---

## Project Structure

- `db/` — Contains database connection utility (`DBConnection.java`)
- `gui/` — Contains GUI classes for Students, Courses, Enrollment, and Student List views
- `logic/` (if applicable) — Contains business logic classes

---

## Database Setup

1. Create a MySQL database named `your_database_name` (replace with your actual DB name).
2. Run the SQL script `database_schema.sql` (if provided) to create tables:
    - `Students`
    - `Courses`
    - `Enrollments`
3. Update the `DBConnection.java` file with your MySQL username, password, and database URL.

Example JDBC URL:
```java
jdbc:mysql://localhost:3306/your_database_name
