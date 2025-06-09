# 🏡 Home Sales Analysis – Module 22 Challenge

This project explores home sales data using **PySpark** and **Spark SQL**.  
It was created for **Module 22: Big Data with Spark** in the Data Analytics Bootcamp.

---

## 📁 Project Structure

- `Home_Sales.ipynb` → Main analysis notebook (Google Colab or Jupyter compatible)  
- `home_sales_revised.csv` → Input dataset (uploaded manually or accessed from AWS)

---

## 🚀 Tools & Technologies

- Python  
- PySpark  
- Spark SQL  
- Google Colab  
- Jupyter Notebook  
- Git & GitHub  

---

## 🎯 Objectives

Analyze real-world housing data using Spark SQL to answer key business questions:

1. 📅 What is the average price of 4-bedroom homes sold each year?  
2. 🛏️ What is the average price of homes by year and bedroom count?  
3. 🛁 What is the average price of homes with more than 2 bathrooms by year?  
4. 🏠 What is the average price of homes with over 2000 square feet by year?  
5. 📁 How does Parquet file performance compare with in-memory cache?  
6. ⚡ What’s the speed difference between cached, uncached, and parquet queries?

---

## 🔍 Sample Output

| Year | Avg Price (4-Bedrooms) |
|------|------------------------|
| 2019 | $300,263.70            |
| 2020 | $298,353.78            |
| 2021 | $301,819.44            |
| 2022 | $296,363.88            |

> 📌 All outputs for every query are shown using `.show()` in the notebook.

---

## 🛠️ Key Concepts Covered

- Loading CSV into a PySpark DataFrame  
- Creating and querying Spark SQL temp views  
- Aggregating and rounding results using SQL  
- Writing and reading data using **Parquet** format  
- Measuring performance with `time` module  
- Using `.cache()` and `.uncache()` for memory management  

---

## ✅ Final Steps Added

- Created temp table from Parquet file  
- Queried and compared runtime from Parquet vs. cached vs. uncached  
- Measured execution time for each approach  
- Verified cache status using `is_cached`  

---

## 🙋‍♀️ Author

**Anqa Javed**  
_Data Analytics Bootcamp Student_  
GitHub: [@AnqaJaved](https://github.com/AnqaJaved)
