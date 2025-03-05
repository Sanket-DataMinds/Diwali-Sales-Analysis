# Diwali Sales Analysis

## Overview
This project analyzes Diwali sales data to uncover key trends, customer demographics, and purchasing behaviors. The dataset contains information about customers, their demographic details, purchase history, and sales performance across various product categories.

## Dataset Information
The dataset consists of **11,251 entries** with the following attributes:
- **User_ID**: Unique identifier for each customer.
- **Cust_name**: Name of the customer.
- **Product_ID**: Unique product identifier.
- **Gender**: Customer's gender (Male/Female).
- **Age Group**: Categorized age range of customers.
- **Age**: Exact age of customers.
- **Marital_Status**: Customer's marital status (0 = Single, 1 = Married).
- **State & Zone**: Geographic location of customers.
- **Occupation**: Customer's profession.
- **Product_Category**: Category of the purchased product.
- **Orders**: Number of orders placed.
- **Amount**: Total purchase amount (in INR).

## Data Cleaning & Preprocessing
- **Handling Missing Values**:
  - The **'Amount'** column had 12 missing values, which were filled using the median value.
  - The **'Status'** and **'Unnamed1'** columns were entirely empty and removed.
- **Data Type Adjustments**:
  - Ensured numerical fields like Age, Orders, and Amount were properly formatted.
  - Standardized categorical fields for consistency.

## Key Insights
### 1. Sales Distribution by Gender
- The majority of buyers were **female customers**.
- Women contributed to a higher total sales amount compared to men.

### 2. Age Group Analysis
- The **26-35 age group** made the most purchases.
- Younger and middle-aged customers were the most active shoppers.

### 3. Geographical Insights
- **Maharashtra, Karnataka, and Uttar Pradesh** had the highest number of purchases.
- Sales were distributed across multiple zones, with the **Western Zone leading** in revenue.

### 4. Occupation-based Sales
- The highest number of purchases came from **IT, Healthcare, and Aviation professionals**.
- Government employees had fewer transactions but with higher average order values.

### 5. Top-Selling Product Categories
- **Electronics, Apparel, and Auto Accessories** were the most purchased product categories.
- High-value items like **Electronics and Auto parts** contributed significantly to the total revenue.

## Visualizations & Dashboards
The Jupyter Notebook contains various **data visualizations**:
- **Bar Charts** for gender-based sales distribution.
- **Pie Charts** for regional sales trends.
- **Heatmaps** showing correlation between age, orders, and purchase amount.
- **Scatter Plots** to identify high-spending customers.

## Conclusion
The Diwali Sales Analysis provides valuable insights into consumer behavior and purchasing trends. Businesses can use these findings to:
- Target high-spending demographics effectively.
- Offer discounts and promotions tailored to top customer segments.
- Optimize inventory by focusing on top-performing product categories.

## How to Use
1. Open the **Jupyter Notebook (Diwali_Sales_Analysis.ipynb)**.
2. Run each cell to explore the dataset and generate insights.
3. Modify the code to perform additional custom analysis as needed.

### Tools Used
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** for data analysis & visualization.
- **Jupyter Notebook** for executing and documenting the analysis.
