# 📘 MySQL Notes
This repository contains my personal notes while learning MySQL and database fundamentals. 
It helps me revise concepts and understand how databases work in real-world applications.

🔹 What is a Database?

A database is a structured system used to store and manage data efficiently. Instead of keeping data randomly, it is organized so that it can be easily accessed, updated, and maintained.

Databases are used in real-world applications like:

Banking systems
E-commerce platforms
Social media apps
🔹 Key Features of Databases
Persistent Storage → Data remains stored even after system restarts
Structured Format → Organized to avoid redundancy
Efficient Retrieval → Fast querying and filtering
Concurrent Access → Multiple users can access data safely
Security → Controlled access and data protection
🔹 Why Use a Database?
Store large amounts of data efficiently
Avoid duplication and maintain consistency
Enable fast data retrieval
Support multiple users simultaneously
Provide backup and recovery options
🔹 Database Management System (DBMS)

A DBMS is software that helps users interact with databases.

Functions:
Data storage
Data retrieval
Data modification
Security management
Examples:
Relational DBMS → MySQL, PostgreSQL, Oracle
NoSQL → MongoDB, Cassandra
In-memory → Redis

👉 Focus: MySQL (Relational DBMS)

🔹 Relational Data Model

In this model, data is stored in the form of tables.

Each table consists of:

Rows (Records) → Actual data
Columns (Attributes) → Data properties
🔹 Core Concepts
📌 Tables

Represent real-world entities like Employees, Customers, Products.

📌 Columns (Attributes)

Define the type of data stored in a table.

Example:

employee_id | name | salary
📌 Rows (Records)

Each row represents a single entry.

Example:

101 | Rahul | 50000
🔹 Keys in Database
🔑 Primary Key
Uniquely identifies each row
Cannot be NULL or duplicate
🔗 Foreign Key
Links one table to another
Maintains relationships between tables
🔹 Table Relationships
1️⃣ One-to-One (1:1)

One record in Table A ↔ one record in Table B

2️⃣ One-to-Many (1)

One record in Table A → multiple records in Table B

Example: One department → many employees

3️⃣ Many-to-Many (M)

Multiple records in both tables are related

Example: Students ↔ Courses

🔹 Advantages of Relational Model
Data Integrity → Ensures valid relationships
Reduced Redundancy → Minimizes duplication
Flexible Queries → SQL allows complex operations
🔹 MySQL Data Types
🔢 Numeric Types
INT → Integer values
FLOAT, DOUBLE → Decimal values
DECIMAL → Precise values (used for money)
🔤 String Types
CHAR(n) → Fixed-length string
VARCHAR(n) → Variable-length string
TEXT → Large text data
📅 Date & Time Types
DATE → YYYY-MM-DD
TIME → HH:MM
DATETIME → Date + Time
TIMESTAMP → Auto-updated time
✔️ Boolean Type
BOOLEAN → TRUE / FALSE (stored as 1/0)
📦 Other Types
BLOB → Binary data (images/files)
ENUM → Predefined list of values
🚀 Next Steps
Learn basic SQL queries (SELECT, INSERT, UPDATE, DELETE)
Practice joins and relationships
Work on real-world database design
✍️ Note

These notes are part of my learning journey in MySQL and database concepts, created for better understanding and revision.

