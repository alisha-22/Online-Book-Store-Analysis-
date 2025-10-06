# Online Bookstore Analysis – SQL Project

An SQL-based data analysis project focused on exploring and understanding the business performance of an online bookstore.

This project demonstrates how to use SQL queries to extract insights, calculate KPIs, and analyze customer and sales data.

🛠 Tools & Technologies

MySQL Workbench (for database management and query execution)

SQL (Data querying, joins, aggregation, and filtering)

 # Database Overview

Database Name: onlinebookstoreproject
Tables Used:

books – Contains details about each book (Title, Genre, Author, Price, Stock, Published Year)

customers – Includes customer information (Name, City, Country)

orders – Holds order details (Order ID, Customer ID, Book ID, Quantity, Total Amount, Order Date)

# Key Queries & Insights
#Query Description	SQL Feature Used
1	Retrieve all books where genre = 'Fiction'	WHERE
2	Find books published after 1950	Comparison operator
3	List all customers from Canada	WHERE
4	Show orders placed in November 2023	BETWEEN + STR_TO_DATE()
5	Calculate total stock available	SUM()
6	Find the most expensive book	ORDER BY + LIMIT
7	Customers who ordered more than 1 book	WHERE
8	Orders where total amount > $20	WHERE
9	List distinct genres available	DISTINCT
10	Display lowest stock books	ORDER BY ASC + LIMIT
11	Total revenue generated	SUM()
12	Total books sold by each genre	JOIN + GROUP BY
13	Average price of books in Fantasy genre	AVG()
14	Customers who placed 2+ orders	HAVING COUNT()
15	Most frequently ordered books	JOIN + GROUP BY + ORDER BY
16	Total books sold by each author	JOIN + GROUP BY
17	Cities where customers spent more than $30	JOIN + WHERE
18	Customers who spent the most	JOIN + SUM() + ORDER BY DESC
19	Remaining stock after all orders	LEFT JOIN + COALESCE()

# Key Insights

Top genre: Fiction and Fantasy dominate in both sales and revenue.

Highest spenders: Repeat customers contribute significantly to total revenue.

Most sold author: Identified by aggregating total books sold.

Remaining stock: Computed after all orders were fulfilled.

# Learnings

Performing multi-table joins (INNER JOIN, LEFT JOIN)

Using aggregate functions (SUM, AVG, COUNT, TRUNCATE)

Query optimization for reporting

Applying business logic to real-world datasets

# How to Run

Download and import the SQL script file Online book Store Analysis.sql into MySQL Workbench.

Run the queries one by one to explore results.

Optionally, connect with visualization tools (like Power BI or Tableau) for data visualization.

# Future Enhancements

Add ER diagram of the database.

Visualize sales and stock trends using Power BI.

Automate daily revenue reporting with Python + SQL integration.

<img width="1920" height="1012" alt="linkedin_post4_1" src="https://github.com/user-attachments/assets/7f034fdd-20c8-45cc-a3fd-0facb257768c" />
