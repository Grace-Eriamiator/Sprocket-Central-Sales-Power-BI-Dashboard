#  Sprocket Central Sales Dashboard

## Overview
This dashboard explores sales performance at Sprocket Central, focusing on the most profitable brands, customer preferences, and regional trends. It visually presents insights on product classes, order patterns, and wealth segments, while also highlighting activity from different states.

---

## Dashboard Pages

### 1. Product Analysis
- Tracks key KPIs: Total Orders, Total Profit, Total Customers, Average Age, and Number of Product Lines
- Bar chart ranking profit by brand
- Pie charts breaking down orders and profit by product class

### 2. Customer Analysis — Demographics & Profitability
- Pie chart showing order distribution by gender
- Donut chart displaying profit contribution by wealth segment
- Ranked table of top customers by total profit

### 3. Customer Analysis — Trends & Behaviour
- Line chart tracking monthly order trends over time
- Clustered column chart comparing order volume across age groups
- Clustered bar chart comparing profit by state and car ownership status

### 4. Recommendations
- Data-driven insights synthesised from the analysis to guide marketing and inventory decisions

---

## Tools & Technologies
- **Power BI Desktop**
- **DAX** (Data Analysis Expressions)

---

##  Data Model

| Table | Key Fields |
|---|---|
| `Transactions` | Total_Order, Total_Profit, product_line, product_class, brand, online_order |
| `CustomerDemographic` | Total_Customer, Average_Age, gender, wealth_segment, Age_group, owns_car |
| `CustomerAddress` | state |
| `NewCustomerList` | state |

---

##  Key Features
- 6 interactive cross-page slicers (Gender, Product Line, Online Order, Wealth Segment, State, Product Class)
- Dynamic KPI cards for at-a-glance performance metrics
- Consistent branded theme using the Sprocket Central identity
- Customer segmentation by age group, wealth segment, gender, and geography

---

##  File
`Sprocket_Central_Sales_Dashboard.pbix`

---

##  How to Use
1. Download the `.pbix` file
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Use the slicers on each page to filter and explore the data interactively

---

##  Notes
- This project is for learning/demo purposes
- Data may be sample or anonymized
