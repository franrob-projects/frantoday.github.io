---
layout: page
title: SQL Cheat Sheet
description: SQL is essential for managing and manipulating structured data in relational databases. 
img: assets/img/sql.jpg
importance: 3
category: code
---

Let's assume we have a table called `holidays` with columns `name`, `date`, and `country`, here are some examples of SQL commands for holidays:

1. Retrieving all holidays:

    This command retrieves all rows and columns from the `holidays` table.

    ```
    SELECT * FROM holidays;
    ```

2. Filtering holidays by country:

    This command retrieves all rows and columns from the `holidays` table where the `country` column is `USA`.

    ```
    SELECT * FROM holidays WHERE country = 'USA';
    ```

3. Retrieving holidays within a date range:

    This command retrieves all rows and columns from the `holidays` table where the `date` column is between May 1, 2023 and December 31, 2023.

    ```
    SELECT * FROM holidays WHERE date BETWEEN '2023-05-01' AND '2023-12-31';
    ```

4. Sorting holidays by date:

    This command retrieves all rows and columns from the `holidays` table and sorts them in ascending order by the `date` column.

    ```
    SELECT * FROM holidays ORDER BY date ASC;
    ```

4. Grouping holidays by month:

    This command retrieves the month (as a number) and the count of holidays for each month from the `holidays` table, grouped by month.

    ```
    SELECT MONTH(date) AS month, COUNT(*) AS count FROM holidays GROUP BY month;
    ```

5. Inserting a new holiday:

    This command inserts a new row into the `holidays` table with the values `Independence Day` for `name`, `2023-07-04` for `date`, and `USA` for `country`.

    ```
    INSERT INTO holidays (name, date, country) VALUES ('Independence Day',
    '2023-07-04', 'USA');
    ```

To learn more, check out the SQL Commands article on [Codecademy](https://www.codecademy.com/article/sql-commands) 