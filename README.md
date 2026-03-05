olatunji Oladeji

Week 0 setup completed by Olatunji Oladeji

## Week 1 – Foundations of Data Analytics

In this week, I learned:
•The difference between data and information
•What data analytics is
•Key data roles and workflows

## Week 2 – Excel for Analysts 1
in this week, i learned some great Excel data cleaning concepts today- 01/02/2026


## Week 3 – Excel for Data Analyst 2
In this week i was able to apply logical functions (IF,AND, OR)to classify data and analyse data using conditional aggregations(COUNTIF,SUMIF,AVEAGEIF) and retrieve information using XLOOKUP nad VLOOKUP where needed. A project is uploaded for reference
I completed a project on data cleaning and analyse using PIVOT table, created a chart and analysis sheet

## Week 4– Data modelling and relational Database Design

In this week, I learnt and documented foundational knowledge of data architecture, focusing on how information is structured, related, and constrained within a relational database management system (RDBMS):
•core concepts mastered include: cardinality and relationships: understanding how data entities interact (1:1, 1:N, M:N)
•scheme design:creating structured blueprints for data storage
•data integrity: implementing primary and foreign keys to ensure ''source of truth'' reliability.
Junction Tables: Resolving complex Many-Many relationships

# E-Commerce Ordering System Database Design

## 📌 Project Overview
This project presents a normalized relational database schema designed to handle the core operations of an e-commerce platform. It manages customers, product inventory, order processing, and payment tracking.

## 🏗️ Schema Architecture
The model consists of 5 primary entities:
* *Customer:* Stores user profile and contact information.
* *Order:* Tracks transactions, total amounts, and dates.
* *Product:* Manages inventory and pricing.
* *OrderItem (Bridge Table):* Resolves the Many-to-Many relationship between Orders and Products, tracking specific quantities and historical prices.
* *Payment:* Records transaction details and payment methods.

## 🚀 Key Design Features
* *Many-to-Many Resolution:* Uses an associative entity (OrderItem) to link products to orders.
* *Data Integrity:* Implements Foreign Key constraints to ensure relational consistency.
* *Scalability:* Designed to support future additions like 'Categories', 'Reviews', or 'Shipping Tracking'.

## 🛠️ Tools Used
* [Draw.io](https://app.diagrams.net/) - Diagramming and Modeling
* SQL - (Mention your dialect here, e.g., MySQL or PostgreSQL)

## 📸 Diagram
![Database ERD](./image.png)
