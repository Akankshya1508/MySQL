# 📘 MySQL Notes
This repository contains my personal notes while learning MySQL and database fundamentals. 
It helps me revise concepts and understand how databases work in real-world applications.



🔹 What is a Database?

A database is a structured way of storing and managing data so that it can be easily accessed, updated, and maintained.

Databases are used in applications like:

Banking systems
E-commerce platforms
Social media applications
🔹 Key Features of Databases
Persistent Storage → Data remains saved even after system restarts
Organized Structure → Helps avoid duplication and inconsistency
Fast Retrieval → Data can be searched and fetched quickly
Concurrent Access → Multiple users can work at the same time
Security → Data is protected from unauthorized access
🔹 Why Use a Database?
To store data permanently
To maintain consistency and avoid redundancy
To handle large amounts of data efficiently
To support multiple users
To enable backup and recovery
🔹 Database Management System (DBMS)

A DBMS is software that allows users to interact with a database.

Functions:
Store data
Retrieve data
Update data
Manage security
Examples:
Relational DBMS → MySQL, PostgreSQL, Oracle
NoSQL → MongoDB, Cassandra
In-memory → Redis

👉 Focus: MySQL (Relational DBMS)

🔹 Relational Data Model

In the relational model, data is stored in the form of tables.

Each table contains:

Rows (Records) → actual data
Columns (Attributes) → type of data
🔹 Core Concepts
📌 Tables

Represent real-world entities like Employees, Customers, Products.

📌 Columns (Attributes)

Define what type of data is stored.

Example:

employee_id | name | salary
📌 Rows (Records)

Each row represents one entry.

Example:

101 | Rahul | 50000
🔹 Keys in Database
🔑 Primary Key
Uniquely identifies each row
Cannot be NULL or duplicate
🔗 Foreign Key
Connects one table to another
Maintains relationships between tables
🔹 Table Relationships
1️⃣ One-to-One (1:1)

One record in Table A is linked to one record in Table B

2️⃣ One-to-Many (1)

One record in Table A is linked to multiple records in Table B

Example: One department → many employees

3️⃣ Many-to-Many (M)

Multiple records in both tables are related

Example: Students ↔ Courses

🔹 Advantages of Relational Model
Data Integrity → ensures valid relationships
Reduced Redundancy → minimizes duplicate data
Flexible Queries → SQL allows complex operations
🔹 MySQL Data Types
🔢 Numeric Types
INT → whole numbers
FLOAT, DOUBLE → decimal values
DECIMAL → precise values (used for money)
🔤 String Types
CHAR(n) → fixed length
VARCHAR(n) → variable length
TEXT → large text
📅 Date & Time Types
DATE → YYYY-MM-DD
TIME → HH:MM
DATETIME → date and time
TIMESTAMP → auto-updated timestamp
✔️ Boolean Type
BOOLEAN → TRUE / FALSE (stored as 1/0)
📦 Other Types
BLOB → binary data (images/files)
ENUM → predefined values
🚀 Next Steps
Learn SQL queries (SELECT, INSERT, UPDATE, DELETE)
Practice joins and relationships
Work on real-world database problems
✍️ Note

These notes are part of my learning journey in MySQL. I created them to improve my understanding and for quick revision.
