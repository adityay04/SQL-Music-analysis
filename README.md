Music Store Data Analysis using SQL

This project focuses on analyzing a relational music store database using SQL to extract meaningful business insights. The dataset simulates a digital music store containing information about customers, invoices, tracks, genres, and sales.

The goal is to answer real-world business questions such as:
-Which genres generate the most revenue?
-Who are the top customers?
-Which countries contribute the most sales?

Tech Stack
-PostgreSQL
-SQL

Database Schema
The database consists of multiple related tables:
-customer – customer details
-invoice – purchase transactions
-invoice_line – individual items in each order
-track – song details
-genre – music categories
-artist / album – music metadata

These tables are connected using primary and foreign keys, forming a relational schema.
-Key SQL Concepts Used
-JOINs (INNER JOIN)
-GROUP BY & Aggregations (SUM, COUNT)
-Subqueries
-Filtering (WHERE, HAVING)
-Sorting (ORDER BY)
-DISTINCT

Business Questions Answered
-Identify top-selling genres
-Find highest spending customers
-Analyze revenue by country
-Determine most popular artists
-Find customers who listen to specific genres (e.g., Rock)

Build a dashboard using Power BI or Tableau
-Add time-based analysis (monthly/yearly trends)
-Perform customer segmentation (high-value users)
-Optimize queries using indexing
