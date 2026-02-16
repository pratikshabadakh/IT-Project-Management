# IT-Project-Management  & Resource Allocation System
📊IT Project Management & Resource Allocation System – SQL Database Design

A structured relational database system designed to manage IT projects, tasks, employees, and resource allocation efficiently.

2️. Description / Purpose:

This SQL-based system is built to manage IT projects by organizing employees, projects, tasks, and resource allocations within a structured relational database.
It ensures proper planning, tracking, and optimization of resources to successfully deliver projects within defined timelines and constraints.

3️. Tech Stack

The project was built using the following technologies:
🗄 Oracle SQL / MySQL
🧱 Relational Database Design
🔑 Primary & Foreign Key Constraints
🧩 ER Modeling
📊 Data Integrity & Relationship Mapping

Concepts Used:
DDL (CREATE TABLE)
Constraints (PRIMARY KEY, FOREIGN KEY, NOT NULL)
One-to-Many Relationships
Schema Design

4️. Data Source

This project uses manually structured sample data for simulation purposes.
Database includes 4 core tables:
Employees
Projects
Tasks
Allocations

Entity Relationships:
One Project → Many Tasks
One Employee → Many Allocations
One Task → Many Allocations

This relational structure ensures data consistency and referential integrity.

5. Features / Highlights:
🔎 Business Problem
In IT organizations, managing multiple projects, tracking tasks, and allocating employees efficiently can become complex. Without a structured system, issues like resource over-allocation, missed deadlines, and poor coordination may occur.

🎯 Goal of the System

The goal of this database system is to:
Organize project information systematically
Track project timelines and status
Allocate employees to tasks efficiently
Maintain structured data relationships
Improve resource optimization

Walkthrough of Key Components
1. Employees Table
Stores employee details such as ID, name, position, and email.

2. Projects Table
Stores project-related information including start date, end date, and status.

3. Tasks Table
Contains tasks under each project with a foreign key relationship to the Projects table.

4. Allocations Table
Acts as a bridge between Employees and Tasks.

Tracks:
Which employee is assigned
Which task they are working on
Allocation date
Hours allocated
This ensures proper workload tracking and resource distribution.

📈 Business Impact & Insights

-Improved project tracking and monitoring
-Better resource allocation and workload balance
-Reduced chances of task duplication
-Structured relational database for scalability
-Strong data integrity using foreign key constraints
-Foundation for future dashboard/report integration

Organizations can use this system as a base for building advanced project management tools with analytics and reporting features.
