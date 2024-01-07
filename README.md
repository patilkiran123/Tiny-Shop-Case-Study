# SQL Case Study: Tiny Shop Sales

<img src="https://d-i-motion.com/wp-content/uploads/2023/05/Tiny-Shop-Sales-600x600.png" alt="Tiny Shop Image" width="300" height="300">

To successfully answer all the questions and extract the data, we should have been exposed to the following areas of SQL:

Basic aggregations, CASE WHEN statements, Joins, Date time functions, CTEs

## Questions

1. Which product has the highest price? Only return a single row.
2. Which customer has made the most orders?
3. What's the total revenue per product?
4. Find the day with the highest revenue.
5. Find the first order (by date) for each customer.
6. Find the top 3 customers who have ordered the most distinct products
7. Which product has been bought the least in terms of quantity?
8. What is the median order total?
9. For each order, determine if it was Expensive' (total over 300), Affordable' (total over 100), or 'Cheap'.
10. Find customers who have ordered the product with the highest price.

## Few Pointers

- Whenever there are non-aggregate and aggregate columns in the **SELECT** clause, it's generally necessary to include those non-aggregated columns in the GROUP BY clause.

- An alias assigned in the SELECT clause **cannot** be used in the GROUP BY clause.

### For Tiny Shop Sales schema **[Click Here](/schema.txt)**

### For SQL Queries **[Click Here](/sql_queries.txt)**

### To View Results **[Watch the Clip](/SQL%20Case%20Study-Tiny%20Shop%20Sales.mp4)**

## Credits

The SQL Case Study: Tiny Shop Sales was completed as part of the [d-i-motion.com](https://d-i-motion.com/lessons/customer-orders-analysis/) lessons on customer orders analysis.

- Website: [d-i-motion.com](https://d-i-motion.com)

---

Feel free to fork this project...
