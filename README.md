# Retail Sales Analytics Dashboard (Power BI)

## Project Overview
This project focuses on building an end-to-end Business Intelligence solution using Power BI. The objective is to analyze retail sales transaction data, transform it into a structured and normalized format, and create an interactive dashboard to support managerial decision-making.

The project demonstrates the complete BI workflow, including data cleaning, normalization, data modeling, DAX measure creation, visualization design, and insight generation.

---

## Objectives
- Analyze retail sales performance using Business Intelligence tools
- Identify revenue trends, product performance, and store-level insights
- Support data-driven decision making through interactive dashboards
- Apply data normalization and star schema modeling concepts

---

## Dataset Description
The dataset represents retail sales transactions and includes information related to:
- Sales transactions
- Products
- Customers
- Store locations
- Payment methods
- Time (date, month, quarter, year)

### Key Characteristics
- More than 500 rows
- Multiple numerical measures (Revenue, Quantity)
- Multiple ID fields
- Date and time attributes
- Normalized up to Third Normal Form (3NF)

The final dataset is stored in Excel and structured into:
- Sales Master (Fact Table)
- Product Master
- Customer Master
- Store Master
- Payment Master
- Date Master

---

## Data Preparation & Normalization
- Data cleaning and transformation performed in Excel
- Revenue column derived from price and quantity
- Duplicate records removed from dimension tables
- Dataset normalized up to 3NF to reduce redundancy and improve integrity
- Foreign keys populated using lookup logic
- Final structure follows a star schema design

---

## Data Modeling (Power BI)
- Central fact table: Sales Master
- Dimension tables: Product, Customer, Store, Payment, Date
- One-to-many relationships established
- Single-directional filtering applied
- Model designed for analytical efficiency and clarity

---

## Key Measures (DAX)
- Total Revenue
- Total Quantity Sold
- Number of Transactions
- Average Revenue per Transaction

These measures dynamically respond to filters and slicers.

---

## Visualizations Included
- KPI Cards (Revenue, Quantity, Transactions, Average Revenue)
- Monthly Revenue Trend (Line / Area Chart)
- Revenue by Product (Bar Chart)
- Revenue by Store Location (Bar Chart)
- Interactive slicers for Year and Payment Method

---

## Business Questions Addressed
- What is the overall sales performance of the organization?
- How does revenue vary across months and years?
- Which products contribute the most to total revenue?
- Which store locations generate the highest revenue?
- What payment methods are most commonly used?
- Are there seasonal patterns in sales performance?

---

## Key Insights
- A few top-performing products generate a large share of total revenue.
- Sales show clear seasonal trends across months.
- Certain store locations consistently outperform others.
- Digital payment methods dominate transaction volumes.
- Average revenue per transaction remains relatively stable.

---

## Tools & Technologies Used
- Microsoft Excel (Data Cleaning & Normalization)
- Power BI Desktop (Data Modeling, DAX, Visualization)
- DAX (Data Analysis Expressions)
- GitHub (Version Control & Project Hosting)

---

## Files Included
- `shop_data_normalised.xlsx` – Normalized dataset
- `Retail_Sales_Analytics.pbix` – Power BI dashboard file
- `README.md` – Project documentation

---

## How to Use
1. Download the Excel dataset and Power BI file
2. Open the `.pbix` file in Power BI Desktop
3. Refresh data if required
4. Navigate through pages to explore insights and visuals

---

## Learning Outcomes
- Practical application of Business Intelligence concepts
- Hands-on experience with data modeling and star schema design
- Understanding of DAX measures and interactive reporting
- Ability to translate data insights into business decisions

---

## Author
Parv 
Business Intelligence & Data Analytics Project



