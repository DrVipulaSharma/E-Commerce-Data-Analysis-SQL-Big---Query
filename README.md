# E-Commerce-Data-Analysis-SQL-Big-Query

## Objective
The primary goal of this project is to analyze the sales, product, and customer demographic data of an e-commerce company using SQL in BigQuery. By examining patterns, trends, and customer behavior, the analysis aims to extract actionable insights and calculate key performance indicators (KPIs) that contribute to profitable growth. This will enable the company to better understand its customers, optimize product strategies, and enhance overall business performance.

## About the DataSet

### 1. Demographics Table:

Description: Contains customer-level demographic information, enabling analysis of purchasing behavior across various customer segments.

Key Columns:

**CustomerID:**  Unique identifier for each customer.

**Age:**  Age of the customer.

**Gender:**  Gender of the customer.

**Income:**  Income level or category of the customer.

**Region:** Geographical region of the customer.

**Education:**  Education level of the customer.

**MaritalStatus:**  Marital status of the customer.

### 2. Transaction Table:

Description: Holds detailed records of sales transactions, serving as the core dataset for understanding sales trends and patterns.

Key Columns:

**TransactionID:**  Unique identifier for each transaction.

**CustomerID:**  Links transactions to customers.

**ProductID:**  Links transactions to products.

**TransactionDate:**  Date of the transaction.

**Quantity:**  Number of items purchased.

**SalesValue:**  Total sales value of the transaction.

**Discount:**  Discounts applied to the transaction.

**StoreID:**  Store where the transaction occurred (if applicable).

### 3. Products Table:

Description: Provides product-level data to analyze trends in product categories, pricing, and performance.

Key Columns:

**ProductID:**  Unique identifier for each product.

**ProductName:**  Name or description of the product.

**Category:**  Product category (e.g., electronics, apparel).

**Brand:**  Product brand.

**Price:**  Unit price of the product.

**StockLevel:**  Availability of the product in inventory.



