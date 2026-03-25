# Bike-Sales-PowerBI-Dashboard
Bike Sales Dashboard - Power BI Project

 Author

Bharath S

---

Project Overview

This project is a Power BI dashboard created using a bike sales dataset. The main objective is to analyze sales performance, profit, customer segments, and regional trends to gain useful business insights.

---

Dataset Description

The dataset contains the following fields:

* Sales, Profit, Quantity, Discount
* Customer Segment
* Product Category and Sub-Category
* Region, State, City
* Order Date and Ship Date
* Return Status

---

Data Cleaning Process (Power Query)

The following steps were performed to clean the data:

* Converted **Order Date** and **Ship Date** into proper date format
* Checked for null values in **Sales** and **Profit** columns
* Replaced null values with **0** to avoid calculation errors
* Replaced missing values in **UB-Category** with **"Unknown"**
* Ensured correct data types for all columns

---

Measures Created (DAX)

The following DAX measures were created:

Total Sales = SUM(Sales)
Total Profit = SUM(Profit)
Total Orders = COUNT(Order ID)
Return Rate= Returned Orders / Total Orders
Profit Margin= Total Profit / Total Sales

---

Dashboard Visuals and Justification

 🔹 KPI Cards

* Used to display **Total Sales, Total Profit, Total Orders, Return Rate**
* Helps in quick overview of business performance

🔹 Donut Chart (Sales by Segment)

* Shows contribution of each customer segment
* Helps identify target customers

🔹 Bar Chart (Sales by Category)

* Compares sales across product categories
* Helps identify best-performing categories

🔹 Line Chart (Sales Trend)

* Displays sales over time
* Helps in understanding growth patterns

🔹 Bar Chart (Top Products)

* Highlights top-performing products
* Helps in product-level decision making

🔹 Map / Bar Chart (Sales by Region)

* Shows geographical sales distribution
* Helps identify strong and weak regions

🔹 Pie Chart (Return Analysis)

* Shows proportion of returned vs non-returned orders
* Helps in analyzing product return issues

---

Filters (Slicers)

Slicers were added for:

* Region
* Category
* Segment
* Order Date

These make the dashboard interactive and user-friendly.

---

Key Insights

* Identified top-performing product categories
* Analyzed customer segments contributing to revenue
* Observed sales trends over time
* Evaluated return rate and its impact on business

---

Tools Used

* Power BI
* Excel
* DAX (Data Analysis Expressions)

---

Files Included

* Bike_Sales_Dashboard.pbix
* bike_sales_dataset.xlsx

---

Conclusion

This dashboard helps in understanding business performance and supports better decision-making using data visualization.
