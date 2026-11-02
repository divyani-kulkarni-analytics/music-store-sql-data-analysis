# SQL Music Store Data Analysis Project

## Project Overview
This project focuses on analyzing a Music Store database using SQL. The main objective is to extract meaningful business insights related to customers, invoices, music genres, artists, and sales performance.

The project uses SQL queries to analyze customer purchasing behavior, identify top-performing artists, and understand sales trends across different countries.

## Tools & Technologies
- **SQL**
- **PostgreSQL**
- **pgAdmin 4**
- **Chinook Music Store Database**

## Business Questions & Analysis

This project covers 11 SQL business questions:

### 1. Employee Analysis
- Identify the senior-most employee based on job title and organizational level.

### 2. Invoice Analysis
- Identify countries with the highest number of invoices.
- Analyze invoice totals.

### 3. Top Invoice Values
- Retrieve invoice totals in descending order.

### 4. Best Performing City
- Identify the city generating the highest revenue based on invoice totals.

### 5. Best Customer
- Find the customer who has spent the highest amount of money.

### 6. Rock Music Listeners
- Retrieve email, first name, last name, and genre information for customers listening to Rock music.
- Sort customers alphabetically by email.

### 7. Top 10 Rock Artists
- Identify the top 10 artists with the highest number of Rock tracks.

### 8. Longest Songs
- Find tracks longer than the average song length.
- Display track names and song duration in milliseconds.

### 9. Customer Spending on Artists
- Identify the best-selling artist.
- Analyze how much each customer has spent on that artist.

### 10. Most Popular Music Genre by Country
- Identify the most purchased music genre in each country.
- Handle situations where multiple genres share the highest purchase count.

### 11. Top Customer by Country
- Identify the customer who has spent the most money in each country.
- Include all customers in case of tied spending amounts.

## SQL Concepts Used

The project demonstrates practical applications of:

- SELECT and DISTINCT
- WHERE and ORDER BY
- GROUP BY and HAVING
- Aggregate Functions (SUM, COUNT, AVG, MAX)
- INNER JOIN
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions (ROW_NUMBER)
- Recursive CTEs
- LIMIT

## Database Tables Used

The analysis uses the following database tables:

- Employee
- Customer
- Invoice
- Invoice_Line
- Track
- Album
- Artist
- Genre

## Key Learning Outcomes

Through this project, I practiced:

- Writing SQL queries to solve real-world business questions.
- Combining multiple tables using JOIN operations.
- Analyzing customer purchasing patterns.
- Calculating revenue and identifying top-performing artists.
- Using CTEs and window functions for advanced SQL analysis.
- Extracting meaningful insights from relational databases.

## Project Files

- `query script.sql` – Contains SQL queries for all 11 business questions.
- `README.md` – Project overview, objectives, and SQL concepts used.

## Conclusion

This project helped me strengthen my SQL skills and understand how database analysis can support business decision-making in the music industry.

**Author:** Divyani Kulkarni  
**Field:** Business Analytics | Data Analytics
