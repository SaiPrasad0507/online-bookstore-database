# 📚 Online Bookstore Database (SQL Project)

A beginner-friendly SQL project simulating a simple online bookstore. It covers table design, relationships, and a range of queries from basic `SELECT` statements to joins, aggregates, and subqueries.

## 🗂️ Project structure

```
├── schema.sql       -- Table definitions (CREATE TABLE)
├── sample_data.sql  -- Sample rows to populate the tables (INSERT)
├── queries.sql       -- Practice queries: basic to intermediate
└── README.md
```

## 🧱 Database design

The database has 4 tables:

| Table        | Description                              |
|--------------|-------------------------------------------|
| `customers`  | People who buy books                      |
| `books`      | Book catalog (title, author, price, etc.) |
| `orders`     | One row per order placed by a customer    |
| `order_items`| Line items linking orders to books        |

**Relationships:**
- One customer → many orders (1:N)
- One order → many order_items (1:N)
- One book → many order_items (1:N)

```
customers ──< orders ──< order_items >── books
```

## ▶️ How to run this project

1. Install any SQL database (MySQL, PostgreSQL, or even SQLite work fine — minor syntax tweaks may be needed for PostgreSQL/SQLite around `AUTO_INCREMENT`).
2. Run `schema.sql` first to create the tables.
3. Run `sample_data.sql` to populate them with sample data.
4. Open `queries.sql` and run the queries one at a time to see the results.

## 🧠 What this project demonstrates

- Table creation with primary keys, foreign keys, and constraints
- Filtering with `WHERE`, `LIKE`, `BETWEEN`, `IN`
- Sorting and limiting results
- Aggregate functions: `COUNT`, `SUM`, `AVG`, `MAX`, `MIN`
- `GROUP BY` and `HAVING`
- `JOIN`s across multiple tables
- Subqueries
- A simple `VIEW`

## 📌 Ideas to extend this project

- Add a `reviews` table and query average rating per book
- Add a `discounts` table and calculate final order totals
- Try rewriting a subquery as a `JOIN` (and vice versa)
- Build a small dashboard in Excel/Python on top of this data

---
Feel free to fork this and adapt it as your own SQL practice project.
