# PR 1: Superstore Sales Analysis (Power BI)

 
**Subject:** Power BI (Practical Report 1)
**Dataset:** [Sample Superstore Sales Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) 

---

## About This Project
This project is an interactive Power BI dashboard built using the **Superstore Sales Dataset** (~9,994 rows). It tracks overall sales, profit, quantity sold, and average discount across different categories and regions.

---

## Tools Used
* **Power BI Desktop** (Power Query Editor & Report View)
* **GitHub** (Project hosting and documentation)

---

## What Was Done

1. **Data Cleaning (Power Query)**
   * Loaded the Superstore dataset and cleaned it in Power Query.
   * Renamed columns (e.g., `Sub-Category` to `Sub Category`) and fixed data types (`Date`, `Decimal`, `Whole Number`).
   * Removed null values and unnecessary columns (`Row ID`, `Country`, `Postal Code`).
   * Filtered `Segment` to keep only **Consumer** and **Corporate*.
   * Split `Order ID` by `-` to extract the region code.

2. **Dashboard Visuals**
   * **4 KPI Cards:** Total Sales, Total Profit, Total Quantity, and Average Discount.
   * **2 Bar Charts:** Sales by Category and Profit by Region (sorted descending with data labels).
   * **2 Slicers:** Region and Category.

3. **Filters, Layout & Interactions**
   * Added a page-level filter for `Ship Mode` (`Standard Class` and `Second Class`) and a visual-level filter for **Top 5 Sub-Categories by Sales**.
   * Styled the report with a built-in theme, custom colors (`#CC0000` and `#4A4A4A`), and a 16:9 layout[cite: 13, 14].
   * Added a second report page with a detailed order **Table*.
   * Configured cross-filtering interactions across visuals.

---

## Files in This Repository
* `README.md` — Project overview and steps
* `Superstore_PR1.pbix` — Completed Power BI report file
* 