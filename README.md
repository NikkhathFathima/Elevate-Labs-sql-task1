

# SQL Developer Internship - Task 1: E-commerce Database Schema

---

## Overview

This repository contains the deliverables for **Task 1** of the SQL Developer Internship, focusing on database setup and schema design. The objective was to apply core database concepts like DDL (Data Definition Language), normalization principles, and ER (Entity-Relationship) diagramming to create a well-structured database.

## Domain Chosen

For this task, I chose the **E-commerce** domain, as it provides a practical scenario to model various entities and their relationships.

## Tools Used

* **MySQL Workbench / [Your SQL Client]**: Used for creating the database, executing the SQL script, and potentially generating the ER Diagram.
* **[ER Diagram Tool, e.g., dbdiagram.io, Lucidchart, or MySQL Workbench's built-in feature]**: Used to visualize the database schema.

## Deliverables

### 1. SQL Schema Script

The `ecommerce_schema.sql` file contains the SQL script necessary to create the entire E-commerce database schema. This script includes:

* Database creation.
* Table definitions for key entities like `Customers`, `Products`, `Orders`, `Categories`, `Suppliers`, and `Order_Items`.
* Definition of **Primary Keys** (`PRIMARY KEY`) for unique identification of records.
* Establishment of **Foreign Keys** (`FOREIGN KEY`) to enforce referential integrity and define relationships between tables.
* Use of `AUTO_INCREMENT` for surrogate primary keys.
* Application of various SQL constraints (e.g., `NOT NULL`, `UNIQUE`, `DEFAULT`, `ENUM`).

### 2. ER Diagram

 the Entity-Relationship Diagram for the designed E-commerce schema. This diagram visually represents:

* All identified entities (tables).
* Their respective attributes (columns).
* The relationships between entities, including cardinality (one-to-one, one-to-many, many-to-many).
* ![ER TASK1](https://github.com/user-attachments/assets/87488ca1-e7fb-45ca-84b4-e1d00f73513d)


## Key Concepts Demonstrated

This task allowed me to apply and demonstrate understanding of the following key database concepts:

* **DDL (Data Definition Language)**: Specifically, `CREATE DATABASE` and `CREATE TABLE` statements.
* **Normalization Principles**: The schema design reflects efforts to reduce data redundancy and improve data integrity, generally aligning with 3rd Normal Form (3NF) by separating entities like customers, products, and orders into distinct tables and linking them via foreign keys.
* **ER Diagrams**: Understanding how to visually represent database structures and relationships.
* **Primary and Foreign Keys**: Their roles in ensuring data uniqueness and referential integrity.
* **SQL Constraints**: Implementing rules to maintain data quality and consistency.

## How to Use the SQL Script

1.  Open your preferred MySQL client (e.g., MySQL Workbench, phpMyAdmin).
2.  Connect to your MySQL server.
3.  Open the `ecommerce_schema.sql` file.
4.  Execute the script. This will create the `ecommerce_db` database and all the necessary tables with their defined relationships and constraints.

