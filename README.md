# Zomato_Food_Case_Study_MYSQL
# 🍽 Zomato Food Delivery Data Analysis Using MySQL

##  Project Overview

This project simulates a real-world Zomato-style food delivery database and performs business-driven data analysis using MySQL.

The objective of this project is to analyze customer behavior, restaurant performance, revenue trends, delivery efficiency, and business growth insights using SQL queries ranging from basic to advanced levels.

This project is designed to demonstrate strong SQL skills for Data Analyst and Business Analyst roles.

---

##  Database Schema

The project consists of the following relational tables:

### Customers
* customer_id (Primary Key)
* name
* location

### Restaurants

* restaurant_id (Primary Key)
* name
* cuisine_type
* location
* rating
* avg_delivery_time

### Orders

* order_id (Primary Key)
* customer_id (Foreign Key)
* restaurant_id (Foreign Key)
* order_date
* total_amount
* status

### Deliveries

* delivery_id (Primary Key)
* order_id (Foreign Key)
* delivery_time
* distance_km
* delivery_fee
* status

### Items

* item_id (Primary Key)
* order_id (Foreign Key)
* item_name
* price
* quantity

---

##  Business Objectives

This project answers real-world business questions such as:

* Which restaurants generate the highest revenue?
* Which cuisine types perform best?
* What is the cancellation rate per restaurant?
* Who are the top customers by spending?
* How does delivery time impact ratings?
* What are the monthly revenue trends?
* Which city offers the best expansion opportunity?

---

##  Key Analysis Areas

###  Customer Analysis

* Total orders per customer
* Customer Lifetime Value (CLV)
* Repeat customer identification
* Top spending customers

###  Restaurant Performance

* Revenue per restaurant
* Revenue per cuisine type
* Cancellation rate analysis
* High rating vs low revenue detection

###  Delivery Performance

* Average delivery time
* Delivery fee per kilometer
* Late delivery identification
* Distance vs fee analysis

###  Revenue & Growth Analysis

* Monthly revenue trends
* Revenue breakdown by status
* Last 30 days performance
* City-wise revenue comparison

---

##  SQL Concepts Used

This project demonstrates the following SQL concepts:

* SELECT statements
* WHERE filtering
* GROUP BY & HAVING
* Aggregate functions (SUM, AVG, COUNT)
* INNER JOIN
* Subqueries
* CASE statements
* Window functions (RANK, PARTITION BY)
* Date functions
* Performance-based ranking queries

---

##  Sample Advanced Business Insights

* Identified highest revenue-generating restaurant per city
* Detected restaurants with high ratings but low revenue
* Calculated cancellation rate by restaurant
* Measured customer lifetime value
* Analyzed revenue growth trends over time

---

##  How to Use This Project

1. Import the CSV files into MySQL.
2. Create the tables using appropriate data types.
3. Load the data using `LOAD DATA INFILE` or MySQL Workbench import wizard.
4. Run the SQL queries provided in the project file.
5. Analyze the results and derive business insights.

---

##  Skills Demonstrated

* Data Cleaning & Transformation
* Business-Oriented SQL Analysis
* Relational Database Understanding
* Revenue & Performance Analytics
* Analytical Thinking
* Problem-Solving Using SQL

---

##  Project Highlights

* 1000+ rows per table
* Multi-table relational database
* Real-world business scenarios
* Easy, Medium, and Advanced SQL questions
* Interview-ready SQL case study

---

##  Author

**Rajendra Thakre**
Aspiring Data Analyst | SQL | Excel | Python | Power BI

---

##  Conclusion

This project demonstrates the ability to work with relational databases and solve real-world business problems using SQL. It highlights analytical thinking, structured problem solving, and the ability to translate raw data into actionable insights.

---

If you found this project useful, feel free to ⭐ the repository.

