1. State and Explain the Components of a DBMS (Database Management System)
A Database Management System (DBMS) is a software system used to manage databases. It allows users to create, read, update, and delete data in a structured and organized manner. The main components of a DBMS include:

Database Engine: Responsible for storing, retrieving, and updating data.
Database Schema: Defines the structure of the database, including tables, columns, and relationships.
Query Processor: Interprets and executes SQL queries.
Database Manager: Manages data access, ensuring concurrency and security.
Transaction Manager: Ensures the integrity of data through transactions.
Data Dictionary: Stores metadata about the database, such as tables, columns, and constraints.
User Interface: Allows users to interact with the database.
2. What is a Relational Database? Give 4 Examples.
A relational database is a type of database that stores data in tables (relations). Each table consists of rows (records) and columns (attributes). Tables can be related to each other using primary and foreign keys.

Examples of relational databases:

MySQL
PostgreSQL
SQLite
Microsoft SQL Server
3. State and Explain Three Classifications of SQL
SQL (Structured Query Language) can be classified into the following categories:

Data Query Language (DQL): Used to query and retrieve data from a database. Example: SELECT.
Data Definition Language (DDL): Used to define or modify the structure of database objects like tables and schemas. Examples: CREATE, ALTER, DROP.
Data Manipulation Language (DML): Used to manipulate data within the database. Examples: INSERT, UPDATE, DELETE.
4. What is the Difference Between a Primary Key and a Foreign Key?
Primary Key: A primary key is a unique identifier for each record in a table. It ensures that no two rows have the same value in the primary key column(s), and it cannot have NULL values.

Foreign Key: A foreign key is a column or set of columns in one table that refers to the primary key in another table. It establishes a relationship between the two tables and enforces referential integrity.

5. What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a visual representation of the entities in a database and their relationships. It consists of:

Entities: Objects or things within the system (represented by rectangles).
Attributes: Properties or details of entities (represented by ovals).
Relationships: Connections between entities (represented by diamonds).
ERDs help in designing and understanding the structure of a database.

6. What are the Advantages of Relational Databases?
Data Integrity: Enforces data consistency and accuracy through constraints (e.g., primary keys, foreign keys).
Flexibility: Supports complex queries and data manipulation using SQL.
Scalability: Can handle large datasets and high transaction volumes.
Security: Provides robust access controls to protect sensitive data.
ACID Compliance: Ensures reliable transactions with properties of Atomicity, Consistency, Isolation, and Durability.
7. State Four Types of Data Types Used to Store Data in Tables
Common data types used to store data in relational databases include:

INT: Used for integer values.
VARCHAR: Used for variable-length strings or text.
DATE: Used for storing date values.
DECIMAL: Used for storing precise numerical values with decimals.
8. What is the Purpose of a Database Management System (DBMS)?
The primary purpose of a DBMS is to provide a structured way to store, manage, and retrieve data efficiently and securely. It ensures data integrity, facilitates concurrent access by multiple users, and provides a robust way to perform operations such as querying, updating, and deleting data. A DBMS also helps in managing the overall architecture of databases and ensuring proper data storage, retrieval, and security.
