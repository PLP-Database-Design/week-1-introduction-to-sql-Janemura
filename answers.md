Q1. Components of a DBMS 
Database Engine: The core service for storing, processing, and securing data. It provides mechanisms for managing transactions and queries.
Query Processor: Converts high-level queries (e.g., SQL) into low-level instructions for the database engine.
Database Schema: Defines the structure of the database, including tables, relationships, and constraints.
Transaction Manager: Ensures data consistency through ACID properties (Atomicity, Consistency, Isolation, Durability).
Metadata Manager: Maintains information about the structure and configuration of the database.
User Interface: Provides tools (like SQL editors or GUIs) for interacting with the database.  

Q2.  What is a relational database? Give 4 examples. 
A relational database organizes data into tables (relations) with rows and columns. Relationships between tables are established using primary and foreign keys, ensuring data integrity and reducing redundancy.

Examples:
MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server   
   
Q3. State and Explain three classifications of SQL?   
DDL (Data Definition Language): Used to define and modify database structures, examples: CREATE, ALTER, DROP, TRUNCATE.

DML (Data Manipulation Language): Used to manipulate data within tables, examples: INSERT, UPDATE, DELETE, SELECT.

DCL (Data Control Language): Used to control access and permissions, examples: GRANT, REVOKE.   

Q4. What is the difference between a Primary Key and a Foreign Key?  
Primary Key is a unique identifier for a record in a table while foreign key is a field in one table that references a primary key in another table.

Primary key ensures no duplicate values and cannot be NULL while foreign key is used to establish relationships between tables.

Primary key example: CustomerID in a Customers table while foreign key example: OrderID in an Orders table referencing CustomerID in a Customers table.

Q5. What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a visual representation of the data model for a system. It illustrates the entities (tables), their attributes (columns), and the relationships (connections) between them. It is used to design and understand the structure and relationships in a database.

Q6. What are the advantages of relational databases?
Data Integrity: Enforces constraints like primary and foreign keys.

Data Redundancy Reduction: Eliminates duplicate data through normalization.

Flexibility: Easily scalable and adaptable to changes.

Secure: Provides robust access control and data protection mechanisms.

Q7. State four types of data type used to store data in tables?
Integer: Stores whole numbers, example: INT.

Text: Stores alphanumeric data, example: VARCHAR, TEXT.

Date/Time: Stores temporal data,example: DATE, DATETIME, TIMESTAMP.

Decimal: Stores precise fractional values,example: DECIMAL, FLOAT.

Q8. What is the purpose of a database management system (DBMS)?
Data Organization: Efficiently organizes data for easy access and management.

Data Security: Provides controlled access and permissions.

Data Consistency: Ensures accurate and consistent data across transactions.

Data Accessibility: Simplifies data querying and reporting through tools and languages like SQL.

Multi-user Support: Allows simultaneous access by multiple users while maintaining data integrity.



