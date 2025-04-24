
# Task 3: SQL for Data Analysis
This repository contains the SQL queries and outputs for **Task 3: SQL for Data Analysis**.

##  Task Description

The goal of this task was to extract and analyze structured data using SQL. The analysis was conducted using an online SQL IDE and included querying a movie revenue dataset. The SQL statements explored selection, filtering, joining tables, aggregate functions, subqueries, and views.

## Dataset

The dataset used includes two tables:
- **movie_revenue**: Contains information about movie titles, budget, box office revenue, release year, and studio ID.
- **studio**: Contains studio names and IDs.

## SQL Environment

The SQL queries were executed using an **online SQL IDE** (such as [SQL Fiddle](https://sqlfiddle.com), [DB Fiddle](https://www.db-fiddle.com), or equivalent).

## SQL Features Demonstrated

- **SELECT, WHERE, ORDER BY, GROUP BY**: Basic data filtering, sorting, and grouping.
- **JOINS**: Demonstrated INNER JOIN, LEFT JOIN, and RIGHT JOIN between movie and studio tables.
- **Subqueries**: Used to filter results based on calculated aggregates.
- **Aggregate Functions**: Used `SUM()` and `AVG()` to analyze total and average revenues.
- **Views**: Created a view to calculate movie profits.
## TASK LINK

https://sqliteonline.com/#sqltext=%23url-sqlite%3Ddb-sqlite%0D%0A%23tab-name%3DSQLite.2%0D%0A--%20INNER%20JOIN%3A%20Movie%20titles%20with%20their%20studios%0ASELECT%20mr.title%2C%20s.studio_name%0AFROM%20movie_revenue%20mr%0AINNER%20JOIN%20studio%20s%20ON%20mr.studio_id%20%3D%20s.studio_id%3B%0A%0A--%20LEFT%20JOIN%3A%20All%20movies%2C%20even%20if%20the%20studio%20is%20missing%0ASELECT%20mr.title%2C%20s.studio_name%0AFROM%20movie_revenue%20mr%0ALEFT%20JOIN%20studio%20s%20ON%20mr.studio_id%20%3D%20s.studio_id%3B%0A%0A--%20RIGHT%20JOIN%3A%20All%20studios%2C%20even%20if%20no%20movie%20is%20associated%0ASELECT%20mr.title%2C%20s.studio_name%0AFROM%20movie_revenue%20mr%0ARIGHT%20JOIN%20studio%20s%20ON%20mr.studio_id%20%3D%20s.studio_id%3B%0A

## Contact

**Saisruthi** [saisruthivasudevan6@gmail.com]
