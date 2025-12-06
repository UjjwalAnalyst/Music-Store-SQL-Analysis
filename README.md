# Music-Store-SQL-Analysis
SQL analysis of a music store database exploring sales, customers, artists, genres, and revenue insights.
This project contains a complete SQL analysis of a Music Store database, exploring customer behavior, artist popularity, genre performance, sales trends, and revenue insights. The goal of this project is to apply real-world SQL techniques—ranging from basic queries to advanced analytics—to extract meaningful insights from a relational database. Through structured queries, multiple joins, subqueries, CTEs, aggregate functions, and window functions, this project demonstrates strong SQL proficiency and analytical thinking.

🔧 Skills & SQL Techniques Used
🟦 Basic SQL

SELECT, WHERE, ORDER BY

DISTINCT

LIMIT

🟩 Joins (Multiple Joins Used)

INNER JOIN

LEFT JOIN

RIGHT JOIN

FULL JOIN (if supported)

Combining 3–4 tables in a single query

Joining tables like:

customer

invoice

invoice_line

track

album

artist

genre

media_type

🟨 Aggregate Functions

SUM()

COUNT()

AVG()

MAX()

MIN()

ROUND()

🟧 Grouping & Filtering

GROUP BY

HAVING

Nested grouping

🟥 Advanced SQL

Subqueries (correlated + non-correlated)

CTEs (WITH clause) for readable complex queries

Window Functions:

ROW_NUMBER()

RANK()

DENSE_RANK()

OVER(PARTITION BY …)

Case Statements for classification

String functions:

UPPER()

LOWER()

LIKE

CONCAT()

🟪 Data Analysis Logic

Revenue analysis

Top customers by spending

Most popular genre

Best-selling artists

Sales by country

Monthly and yearly trends

Media type performance

📊 Key Insights Generated

Identified top-spending customers and their purchase patterns

Found highest revenue generating artists

Analyzed genres with maximum plays and purchases

Compared sales across countries and cities

Determined top tracks and top albums by revenue

Calculated customer lifetime value using window functions

Used multiple joins to connect invoice → invoice_line → track → genre → artist

Identified best-selling media types

Analyzed monthly revenue trends to understand peak periods

📂 Project Structure
music-store-sql-analysis/
│── README.md
│── data/
│   └── music_store_database.sql (or CSV files)
│
│── queries/
│   ├── basic_queries.sql
│   ├── joins_analysis.sql
│   ├── genre_artist_analysis.sql
│   ├── sales_revenue_queries.sql
│   ├── advanced_sql_queries.sql
│   └── window_functions_queries.sql
│
└── results/
    └── insights.md

🎯 Objective

To analyze the Music Store’s relational database using SQL and transform raw tables into actionable insights about sales, customers, artists, and music trends using advanced analytical queries.
