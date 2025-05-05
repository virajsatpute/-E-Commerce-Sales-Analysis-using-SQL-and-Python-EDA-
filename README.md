
---

## 🛒 E-Commerce Sales Analysis using SQL and Python (EDA Project)

### 📌 Project Overview

This project performs a detailed exploratory data analysis (EDA) of an e-commerce dataset using **SQL** and **Python**. The dataset was ingested into a SQL database and queried using a **SQL connector in Python**. SQL was used to retrieve and manipulate the data, while Python libraries were used for further analysis and visualization. The goal is to uncover insights related to customer behavior, sales trends, seller performance, and key performance indicators (KPIs).

---
### 📂 Dataset Description

A basic data pipeline was used in this project. The process involved the following sequential steps:

1. **Data Ingestion**

   * The raw `.csv` files (from [Kaggle Target Dataset](https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv)) were imported and stored into a SQL database.
   * This ingestion was handled using SQL tools or scripts to load each CSV as a separate table (e.g., `orders`, `payments`, `products`, etc.).

2. **Data Extraction**

   * SQL queries were written to extract relevant subsets of the data directly into Python using a SQL connector (e.g., `mysql-connector-python`).
   * This served as the bridge between the database and Python environment.

3. **Data Transformation**

   * Inside SQL: Aggregations, filtering, window functions (e.g., `DENSE_RANK`, `LAG`, `MOVING AVERAGE`) were applied to structure the data.
   * Inside Python: DataFrames were cleaned and formatted using `pandas`.

4. **Data Analysis and Visualization**

   * After transformation, `matplotlib` and `seaborn` were used to visualize trends, compare seller/customer metrics, and uncover insights.

Dataset includes the following tables:

* `customers`: Customer details including ID and location
* `orders`: Order-level info like purchase dates and statuses
* `order_items`: Product-wise details per order
* `payments`: Payment types and transaction amounts
* `products`: Product metadata like category and size
* `sellers`: Seller location and identity
* `geolocation`: Geographical coordinates for customer and seller zip codes

---

### 🛠️ Tools & Technologies

* **SQL** (Window functions, aggregations, joins, CTEs)
* **Python** (`pandas`, `numpy`, `matplotlib`, `seaborn`)
* **Jupyter Notebook** (for code, analysis, and visualization)
* **SQL Connector (MySQL / PostgreSQL)** for connecting and querying the database

---

### 📊 Key Insights

* Identified top-selling product categories and their average prices
* Analyzed correlation between product pricing and order frequency
* Ranked sellers by total revenue and visualized seller performance
* Calculated customer retention rate and cumulative monthly sales
* Computed year-over-year growth and moving averages of customer order values
* Highlighted top 3 high-value customers in each year

---

### 🚀 Next Steps

* Integrate this analysis into a **Power BI dashboard** for interactive insights
* Perform **RFM analysis** for customer segmentation
* Add **predictive modeling** to forecast future sales trends

---

