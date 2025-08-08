# 🎬 Movie Analysis SQL Project

## 📌 Project Overview
This project focuses on analyzing a movies dataset using **SQL** to answer business-related questions, perform data aggregation, and apply advanced SQL concepts like **CTEs** and **Window Functions**.

The goal of this project is to:
- Practice SQL skills from basic to advanced.
- Work with multiple related tables (`Movies_2025`, `Language`, `Director`, `Genre`).
- Derive insights useful for decision-making in the entertainment industry.

---

## 🗂 Dataset Description
The dataset contains information about movies, including:
- **Movies_2025** → Title, Release Date, Genre ID, Director ID, Language ID, IMDb Rating, Budget, Worldwide Collection, OTT Platform, Lead Actor/Actress.
- **Language** → LanguageID, Language Name.
- **Director** → Director_ID, Director Name.
- **Genre** → GenreID, Genre Name.

---

## 🔍 SQL Concepts Used
- **Basic Queries** – `SELECT`, `WHERE`, `ORDER BY`
- **Aggregations** – `COUNT()`, `AVG()`, `ROUND()`
- **Joins** – `INNER JOIN`
- **Grouping** – `GROUP BY`, `HAVING`
- **Sorting & Limiting** – `ORDER BY`, `TOP`
- **Common Table Expressions (CTEs)**
- **Window Functions** – `RANK() OVER (PARTITION BY ...)`
- **Filtering with Subqueries**

---

## 📊 Queries Implemented

### **Easy Level**
1. List all movies with their title and IMDb rating.
2. Find movies released after 2020.
3. Get the total number of movies in the database.

### **Moderate Level**
1. Top 5 movies with highest worldwide collections.
2. Average IMDb rating by language.
3. Top 3 directors based on average IMDb rating.

### **Advanced Level**
1. Top-grossing movie for each genre (after 2015, IMDb > 6).
2. For each director, find their most profitable movie with genre, language, and OTT platform.
3. Actor with highest-grossing movie in each language.

---

## 🛠 How to Use
1. Download the SQL file from this repository.
2. Import the dataset tables into your SQL environment (MySQL / SQL Server / PostgreSQL).
3. Run the queries in `movie_analysis.sql` to get insights.

---

## 📌 Key Insights
- Identified genres that perform best in box office collections.
- Found top directors and actors by profitability and audience rating.
- Compared performance of movies across languages and OTT platforms.

---

## 🚀 Skills Demonstrated
- **SQL Query Writing**
- **Data Aggregation & Filtering**
- **Joins & Relationships**
- **Window Functions & CTEs**
- **Analytical Thinking**

---

## 📬 Contact
**Author:** Kavyanshu Pawar  
📧 Email: pawarkavyanshu123@gmail.com  
🔗 LinkedIn: [Kavyanshu Pawar](https://www.linkedin.com/in/kavyanshu-pawar/)  
