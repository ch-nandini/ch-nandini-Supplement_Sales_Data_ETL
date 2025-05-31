## Supplement_Sales_Data_ETL

## 🚀 Project Overview

This project demonstrates a simple yet powerful ETL process:

- 📥 **Extract**: Load sales data from a CSV file
- 🧹 **Transform**: Clean and enrich the data using Python (Pandas)
- 📊 **Load**: Visualize the cleaned data in Tableau through dynamic, interconnected charts

---

## 📁 Dataset Details

The dataset includes the following fields:

- `Category`
- `Date`
- `Location`
- `Platform Sold`
- `Product Name`
- `Discount`
- `Price`
- `Revenue`
- `Units Returned`
- `Units Sold`

> 📌 *Sample dataset is included in the `/data` folder.*

---

## ⚙️ Technologies Used

- **Python** (Pandas, Jupyter Notebook)
- **Tableau Public/Desktop**
- **CSV Files** for raw and cleaned data

---

## 🧪 ETL Process

1. Extract
Load the raw CSV using Pandas

2. Transform
Handle missing values

Convert data types (e.g., Date)

Remove duplicates and trim whitespace

Add calculated columns like Revenue

Save cleaned data as sales_data.csv

3. Load
Import the cleaned CSV into Tableau

Build an interactive dashboard using charts listed below

📊 Dashboard Visualizations
All visuals are interconnected, enabling dynamic filtering across views:

🔹 Total KPIs (Revenue, Units Sold, Units Returned, Avg. Discount)

📈 Revenue Over Time

📊 Units Sold by Category

🧭 Revenue by Platform Sold

🏆 Top 10 Products by Revenue

🟢 Total Revenue by Category

🎯 Use filters like Category, Platform Sold, and Product Name to interact with the dashboard in real time.

📚 Learnings
Basics of ETL using Python

Data cleaning best practices

Visual storytelling using Tableau

Building filterable, interactive dashboards

🔗 Live Tableau Dashboard
[Tableau Link](https://public.tableau.com/views/Supplement_Sales_Data_Visualisation/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
