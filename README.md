
---

## 🛒 E-Commerce Sales Analysis using SQL and Python (EDA Project)

### 📌 Project Overview

This project performs a detailed exploratory data analysis (EDA) of an e-commerce dataset using **SQL** and **Python**. The dataset was ingested into a SQL database and queried using a **SQL connector in Python**. SQL was used to retrieve and manipulate the data, while Python libraries were used for further analysis and visualization. The goal is to uncover insights related to customer behavior, sales trends, seller performance, and key performance indicators (KPIs).

---

### 📂 Dataset Description

The dataset used in this project is sourced from Kaggle:
🔗 [Target E-Commerce Dataset on Kaggle](https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv)

It includes the following tables:

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

