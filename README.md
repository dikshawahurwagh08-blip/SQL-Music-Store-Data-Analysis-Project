# 🎵 Music Store Data Analysis Using PostgreSQL

## 📌 Project Overview

The Music Store Data Analysis project is designed to analyze a music store database using PostgreSQL. The database contains information about customers, employees, artists, albums, tracks, genres, invoices, and playlists.

The primary goal of this project is to perform business analysis using SQL queries and generate meaningful insights that help understand customer purchasing behavior, popular music genres, top artists, and revenue trends.

---

## 🎯 Project Objectives

* Analyze customer purchasing patterns.
* Identify top-spending customers.
* Determine the most profitable cities and countries.
* Find the most popular music genres.
* Discover top-performing artists and albums.
* Generate business insights using PostgreSQL queries.

---

## 🛠 Technologies Used

| Technology | Purpose                      |
| ---------- | ---------------------------- |
| PostgreSQL | Database Management System   |
| SQL        | Data Analysis Queries        |
| pgAdmin 4  | Database Administration Tool |
| Git        | Version Control              |
| GitHub     | Project Repository           |

---

## 🗄 Database Schema

### Music Store Database Schema

<img width="715" height="577" alt="image" src="https://github.com/user-attachments/assets/800eb61f-f4d4-49a0-b780-00c78ca98df1" />


The schema illustrates the relationships among various tables used in the project.

---

## 📊 Database Tables

### Main Tables Used

| Table Name    | Description                          |
| ------------- | ------------------------------------ |
| Artist        | Stores artist information            |
| Album         | Stores album details                 |
| Track         | Stores song information              |
| Genre         | Stores music categories              |
| MediaType     | Stores media format information      |
| Playlist      | Stores playlist information          |
| PlaylistTrack | Mapping between playlists and tracks |
| Employee      | Stores employee details              |
| Customer      | Stores customer information          |
| Invoice       | Stores customer purchases            |
| InvoiceLine   | Stores purchased track details       |

---

## 🔗 Database Relationships

* Artist → Album (One-to-Many)
* Album → Track (One-to-Many)
* Genre → Track (One-to-Many)
* Customer → Invoice (One-to-Many)
* Invoice → InvoiceLine (One-to-Many)
* Track → InvoiceLine (One-to-Many)
* Employee → Customer (One-to-Many)

---

## 📋 Project Questions

### Easy Level

1. Who is the senior-most employee based on job title?
2. Which countries have the most invoices?
3. What are the top 3 invoice totals?
4. Which city generates the highest revenue?
5. Who is the best customer based on total spending?

### Moderate Level

1. Find all Rock music listeners.
2. Identify the top 10 Rock artists.
3. Find tracks longer than the average song length.

### Advanced Level

1. Calculate customer spending on artists.
2. Determine the most popular genre in each country.
3. Identify the top customer in every country.

---

## 💡 SQL Concepts Used

* SELECT Statements
* WHERE Clause
* ORDER BY
* GROUP BY
* HAVING Clause
* INNER JOIN
* Aggregate Functions

  * COUNT()
  * SUM()
  * AVG()
  * MAX()
* Common Table Expressions (CTE)
* Window Functions
* Subqueries

---

## 📈 Key Insights

* Identified the highest-spending customers.
* Found the most profitable cities.
* Determined the most popular music genres.
* Analyzed artist performance.
* Evaluated country-wise purchasing trends.
* Generated valuable business insights using PostgreSQL.

---

## 🚀 Future Scope

* Develop an interactive Power BI Dashboard.
* Implement advanced visualizations.
* Perform predictive analytics.
* Build a music recommendation system.
* Enable real-time sales monitoring.

---

## ✅ Conclusion

This project demonstrates how PostgreSQL can be used to analyze large datasets and generate meaningful business insights. Through SQL queries, customer behavior, sales performance, music preferences, and revenue trends can be effectively analyzed to support data-driven business decisions.

