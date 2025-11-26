# 🍕 The Great Pizza Analytics Challenge

A SQL-based data analytics project where I worked as a Data Analyst for IDC Pizza.  
My goal was to analyze pizza sales data and convert raw data into actionable business insights.

## 📌 Objectives
- Database creation & table exploration
- Filtering & logical operators
- Aggregations (SUM, AVG, COUNT, MIN, MAX)
- Advanced Joins (INNER, LEFT, RIGHT, SELF)
- Data cleaning with COALESCE, DISTINCT, handling NULLs

 ## Solved Questions

**Phase 1: Foundation & Inspection**

1. Install IDC_Pizza.dump as IDC_Pizza server
2. List all unique pizza categories (`DISTINCT`).
3. Display `pizza_type_id`, `name`, and ingredients, replacing NULL ingredients with `"Missing Data"`. Show first 5 rows.
4. Check for pizzas missing a price (`IS NULL`).

**Phase 2: Filtering & Exploration**

1. Orders placed on `'2015-01-01'` (`SELECT` + `WHERE`).
2. List pizzas with `price` descending.
3. Pizzas sold in sizes `'L'` or `'XL'`.
4. Pizzas priced between $15.00 and $17.00.
5. Pizzas with `"Chicken"` in the name.
6. Orders on `'2015-02-15'` or placed after 8 PM.

**Phase 3: Sales Performance**

1. Total quantity of pizzas sold (`SUM`).
2. Average pizza price (`AVG`).
3. Total order value per order (`JOIN`, `SUM`, `GROUP BY`).
4. Total quantity sold per pizza category (`JOIN`, `GROUP BY`).
5. Categories with more than 5,000 pizzas sold (`HAVING`).
6. Pizzas never ordered (`LEFT/RIGHT JOIN`).
7. Price differences between different sizes of the same pizza (`SELF JOIN`).

take a look at the project report: https://github.com/tejaswinivarma12/The-Great-Pizza-Analytics/blob/main/THE%20GREAT.pdf

## 🔍 Insights Discovered
- Classic pizzas are the **most sold category**
- Identified pizzas **never ordered**
- Price differences between pizza sizes
- Total order revenue per customer order  
- Sales performance across multiple categories

## 🛠 Tech Stack
- MySQL Workbench
- SQL (Joins, Group By, Having, Subqueries)

## 📂 Deliverables
- Organized SQL queries in CSV format
- Full analysis & visual presentation
- Business interpretation of results

---

⭐ Feel free to explore and suggest improvements!  
