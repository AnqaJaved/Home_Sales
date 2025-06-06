# 🏡 Home Sales Analysis – Module 22 Challenge

This project uses **PySpark** and **Spark SQL** to analyze real estate sales data.  
It was completed as part of the Data Analytics Bootcamp (Module 22 - Big Data with Spark).

---

## 📁 Project Structure

- `Home_Sales.ipynb`: The main Colab notebook with all analysis steps
- Data Source: `home_sales_revised.csv` (loaded from AWS or local upload)

---

## 🚀 Technologies Used

- Python
- PySpark
- SparkSQL
- Google Colab
- Git & GitHub

---

## ✅ Objectives

The goal was to answer real-world questions using **PySpark SQL** on a home sales dataset.

---

## 🔍 Questions Answered

1. **What is the average price of a four-bedroom house sold for each year?**
2. **What is the average price of homes by year and bedroom count?**
3. **What is the average price of homes with more than 2 bathrooms by year?**
4. **What is the average price of homes with over 2000 square feet by year?**

---

## 📊 Sample Output (from SQL queries)

| Year | Avg Price (4-Bedrooms) |
|------|------------------------|
| 2019 | $300,263.70            |
| 2020 | $298,353.78            |
| 2021 | $301,819.44            |
| 2022 | $296,363.88            |

*All outputs are shown in the notebook with `.show()` results.*

---

## ✍️ How It Works

- Loaded CSV file into a PySpark DataFrame
- Created a temporary view: `home_sales`
- Used SQL queries to group, filter, and aggregate data
- Rounded all averages to two decimal places

---

## 🙋‍♀️ Author

**Anqa Javed**  
Data Analytics Bootcamp Student  
GitHub: [@AnqaJaved](https://github.com/AnqaJaved)

---

## 📌 Note

This assignment was completed using **Google Colab**, but the notebook can also run on **Jupyter Notebook** with proper Spark setup.

