# 🛒 E-Commerce Sales Insights Analysis using Python & SQL
This project delivers a complete end-to-end Sales Insights Analysis using a multi-table e-commerce dataset. It includes Python-based data loading, cleaning, preprocessing, MySQL data modeling, advanced SQL analytics, and visualization-driven insights

# 📌 Overview

- Multiple e-commerce datasets were loaded, cleaned, and preprocessed using Python.
- Missing values, date formats, and duplicates were handled to prepare high-quality data.
- Cleaned tables were uploaded into a MySQL database for structured analysis.
- SQL queries were used to analyze sales trends, customer behavior, and seller performance.
- Python visualizations helped present key insights clearly and effectively.

# 📊 Dataset Summary

The project uses 7 interconnected tables:
- customers – customer_id, city, state
- geolocation – latitude & longitude of zip codes
- orders – timestamps and delivery details
- order_items – product, seller, quantity, price
- products – product attributes (size, weight, length, etc.)
- payments – payment type, installments, price
- sellers – seller location details

**📂 Dataset used:**  <a href="https://github.com/vipin-s27/E-Commerce-Sales-Analysis-Python-SQL/tree/main/E-Commerce%20Dataset">E-Commerce Dataset</a>

**💻 Project Code:**  <a href="https://github.com/vipin-s27/E-Commerce-Sales-Analysis-Python-SQL/blob/main/python%2Bsql_ecommerce.ipynb">View Notebook</a>

# 🧹 Data Cleaning & Preprocessing

The raw e-commerce dataset was cleaned and preprocessed using Python and SQL to prepare it for analysis. The following steps were performed:

- Loaded Data: Imported 7 tables (customers, geolocation, orders, order_items, payments, products, sellers) and checked their structure.
- Handled Missing Values: Filled numerical columns with medians and categorical columns with "unknown".
- Removed Duplicates: Checked all tables and removed duplicate rows where necessary.
- Converted Dates: Converted relevant columns in orders to datetime format.
- Uploaded to MySQL: Cleaned tables were stored in a MySQL database for efficient querying and analysis.

# 📈 Key Sales Metrics & Visual Analysis

### 1️⃣ Number of Orders per Month in 2018

<img width="793" height="310" alt="image" src="https://github.com/user-attachments/assets/a914ad95-f2c0-4192-8f80-cc6fe3408b6a" />

This bar chart shows the number of orders placed each month in 2018, highlighting peak and low sales periods.


### 2️⃣ Average Number of Products per Order by Customer City

<img width="480" height="360" alt="image" src="https://github.com/user-attachments/assets/ae9d1d82-9c9c-414d-8cff-8794ff98e4d3" />

This bar chart displays the average number of products per order for different customer cities, highlighting cities where customers tend to buy more items per order.


### 3️⃣ Percentage of Total Revenue Contributed by Each Product Category

<img width="671" height="343" alt="image" src="https://github.com/user-attachments/assets/7f712c91-ed3c-4052-a388-992fd6add265" />

This analysis calculates the contribution of each product category to the total revenue. The bar chart highlights the top 5 categories generating the most sales.


### 4️⃣ Cumulative monthly sales – 2017

<img width="397" height="357" alt="Screenshot 2025-12-03 191004" src="https://github.com/user-attachments/assets/9465f811-36b9-4bd9-8221-b74bb10ec163" />

This table shows the cumulative sales for each month in 2017, highlighting monthly sales growth trends and seasonal patterns throughout the year.


### 5️⃣ Top 3 Customers by Spending per Year

<img width="528" height="500" alt="image" src="https://github.com/user-attachments/assets/2a5faacf-6454-417e-9357-7db5e6d97da0" />

This section shows the top 3 customers who spent the most money in each year. It highlights the highest-value customers and helps identify key buyers over time.

# 🛠️ Tools & Technologies

- Python: Pandas, NumPy, Matplotlib, Seaborn for data manipulation, analysis, and visualization
- MySQL Server: For structured data storage, complex queries, and aggregation
- Jupyter Notebook / VS Code: Development and analysis environment
- SQLAlchemy / PyMySQL: Python-MySQL integration for uploading and querying datasets

# 🔧 Project Workflow

### 1. Data Loading & Exploration
- Imported 7 interconnected e-commerce tables using Pandas
- Reviewed structure and summary statistics using .info(), .describe(), and .head()
- Checked for missing values, duplicates, and inconsistent data

### 2. Data Cleaning & Preprocessing
- Filled missing numeric values with median; categorical fields with "unknown"
- Removed duplicate rows where necessary
- Converted date columns to datetime format for analysis
- Uploaded clean tables to MySQL for structured querying

### 3. SQL Analysis
- Basic Metrics: Number of orders per year, unique customer cities, orders per state
- Intermediate Analysis: Average products per order per city, revenue share by product category, top sellers
- Advanced Analysis: Cumulative monthly sales, moving average of customer order value, year-over-year growth, top 3 customers by spending per year

### 4. Visualization
- Bar charts for monthly orders, customer distribution, revenue contribution by category, and top sellers
- Line charts / cumulative plots for monthly sales trends
- Heatmaps or correlation charts for price vs purchase frequency

# 💡 Key Insights from the Analysis
### 1. Sales Trends & Seasonality
- Orders show clear peaks and dips over months in 2018
- Cumulative monthly sales reveal growth trends and seasonal patterns

### 2. Customer Behavior
- Certain cities have higher average products per order
- Top 3 customers per year contribute significantly to total revenue

### 3. Product & Revenue Insights
- Top product categories contribute the highest revenue
- Product price and purchase frequency show moderate correlation

### 4. Payment Insights
- A notable percentage of orders were paid in installments

# 📬 Contact

**Email:**  <a href="mailto:vipinsuryavanshi.vs@gmail.com">vipinsuryavanshi.vs@gmail.com</a>  

**LinkedIn:**  <a href="https://linkedin.com/in/vipin-suryavanshi">Vipin Suryavanshi </a>

**GitHub:**  <a href="https://github.com/vipin-s27">Vipin-s27 </a>





