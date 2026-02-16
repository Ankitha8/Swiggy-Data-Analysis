# Swiggy-Data-Analysis
# 🍽️ Swiggy Data Analysis using SQL Server

## 📌 Project Overview

This project analyzes a Swiggy food delivery dataset using **SQL Server Management Studio (SSMS)**.
The goal is to perform **data cleaning, validation, and business analysis** to extract meaningful insights.

---

## 🛠️ Tools Used

* SQL Server
* SQL Server Management Studio (SSMS)
* Kaggle Dataset

---

## 📂 Dataset Details

The dataset contains food order details including:

* State
* City
* Order Date
* Restaurant Name
* Location
* Category
* Dish Name
* Price (INR)
* Rating
* Rating Count

---

## 🧹 Data Cleaning Performed

✔ Checked NULL values
✔ Removed duplicate rows
✔ Checked blank records
✔ Validated price and rating columns

---

## 📊 SQL Analysis Performed

### 🔹 Dataset Overview

* Total orders
* Total states & cities
* Unique dishes and restaurants

### 🔹 City-wise Insights

* Cities with highest orders
* Cities with highest ratings
* Cities with most expensive food

### 🔹 Price Insights

* Minimum, maximum, and average price
* Dishes above average price

### 🔹 Rating Insights

* Overall average rating
* Most popular dishes based on rating count

### 🔹 State-wise Insights

* Orders per state
* Best-rated states

### 🔹 Business Insights

* Restaurants with most dish variety
* Most reviewed restaurants

### 🔹 SQL Views Created

* City order summary
* Top dishes view

---

## 📈 Sample SQL Query

```sql
SELECT TOP 10 [City], COUNT(*) AS total_orders
FROM dbo.Swiggy_Data
GROUP BY [City]
ORDER BY total_orders DESC;
```

---

## 📌 Key Insights

* Identified top-performing cities and restaurants
* Found price distribution trends
* Determinined most popular dishes
* Analyzed customer rating behavior

---

## 🚀 How to Run This Project

1. Import dataset into SQL Server.
2. Open SSMS.
3. Run provided SQL queries.
4. Analyze results.

---

## 📚 Learning Outcomes

* Data Cleaning in SQL
* Aggregations & Grouping
* Window Functions
* Real-world Data Analysis
* Writing Business Insight Queries

---

## 👩‍💻 Author

**Ankitha D**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
