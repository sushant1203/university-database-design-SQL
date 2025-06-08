# University Database Management System

## 🚀 Project Overview

This project is a comprehensive relational database system designed to model and manage the core academic and administrative operations of a university. The system provides a structured and scalable backend to handle interconnected data related to students, instructors, courses, and institutional departments.

The primary objective was to architect a robust database schema that accurately reflects the complex relationships within an academic environment. This ensures data integrity, minimises redundancy, and enables efficient data retrieval. The project serves as a practical demonstration of advanced database design, data modelling, and the implementation of business logic at the data layer.

---

## ✨ Key Features

* **Student & Course Management:** Full lifecycle management of student records, including enrolment, academic progress (credits), and course cataloguing.
* **Instructor & Departmental Structuring:** Clear hierarchical organisation of departments, their budgets, and the instructors affiliated with them.
* **Complex Relationship Mapping:**
    * Manages the crucial **student-to-advisor** relationship.
    * Implements a **recursive instructor-to-instructor** advisory (mentorship) relationship.
* **Dynamic Scheduling System:** Associates course sections with specific classrooms and time slots, preventing scheduling conflicts.
* **Prerequisite Enforcement:** The schema includes self-referencing relationships on the course entity to enforce academic prerequisites, ensuring logical progression for students.

---

## 📊 Database Schema Design

The database is architected around a set of normalized tables that represent the core entities of the university. The design prioritizes data integrity and query efficiency by establishing clear primary keys, foreign key constraints, and logical relationships between entities.
An Entity-Relationship Diagram (ERD) was created to visualize the database architecture, entities, attributes, and their relationships.

---

## 💻 Technologies Used

* **Database:** MySQL
* **Schema Design:** Entity-Relationship Diagram (ERD), Database Normalisation (3NF)
* **Language:** SQL
* **Tooling:** MySQL Workbench


---

## 🧠 Core Concepts Demonstrated

This project showcases a strong understanding of fundamental and advanced database concepts:

* **Relational Database Design:** Translating real-world requirements into a logical and normalised schema (3NF).
* **Advanced SQL Querying:** Designing and executing complex queries involving multiple `JOIN`s, subqueries, and aggregate functions.
* **Data Integrity and Constraints:** Effective use of `PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, and `CHECK` constraints.
* **Entity-Relationship Modeling:** Mapping complex relationships, including one-to-many, many-to-many, and recursive (self-referencing) relationships.
* **Data Modelling for Business Logic:** Implementing rules such as course prerequisites and class capacity directly into the database schema.

---

## 📄 Project Report

A detailed report outlining the project's scope, design choices, and implementation details is available.

[View the Project Report (PDF)](https://github.com/sushant1203/university-database-design-SQL/blob/main/Project_CO2102_UniversityDatabaseDesignSQLQuery.pdf)

---

## 🔮 Future Improvements

* **Develop a RESTful API:** Build an API layer (e.g., using Node.js/Express or Python/Flask) to allow for programmatic access.
* **Create a Web-Based Frontend:** Design a user interface for students and administrators to interact with the system.
* **Implement User Authentication & Roles:** Introduce role-based access control to secure the data.
* **Automated Reporting:** Add functionality to generate reports on departmental budgets, student enrollment, and classroom utilisation.

---

## 📄 License

* © [2025] [Sushant Jasra Kumar] All Rights Reserved.

---
