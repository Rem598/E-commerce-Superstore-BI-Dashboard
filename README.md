# 🛒 E-commerce Sales and Profit Analysis Dashboard 

## 🎯 Project Goal

The objective of this project was to build a comprehensive, interactive Business Intelligence dashboard using the Superstore dataset. The primary focus was on demonstrating **full-cycle data analysis capabilities**—from raw data transformation to delivering **actionable, profit-driving recommendations** to management.

## 🛠️ Skills Applied

| Phase | Tool/Skill | Description |
| :--- | :--- | :--- |
| **Data Cleaning** | **Power Query (M Language)** | Imported raw CSV data, transformed key columns (e.g., converting Excel Serial Numbers to Date format), and handled basic data validation. |
| **Data Modeling** | **Power BI Relationships** | Established a relational model connecting the core Orders (Fact) table to Returns and Regional Managers (Dimension) tables for accurate data filtering. |
| **Advanced Analysis** | **DAX (Data Analysis Expressions)** | Implemented essential Key Performance Indicators (KPIs) and complex measures like **Net Sales (excluding returns)**, Total Profit, and Profit Margin % for reliable reporting. |
| **Visualization** | **Power BI Visualization** | Designed an interactive dashboard featuring time-series analysis, Top N product performance, and geospatial mapping to identify trends and regional weaknesses. |

## 📊 Dashboard Visualizations

The dashboard provides a holistic view of the business, enabling quick filtering by Region and Time.

![Power BI Superstore Dashboard Screenshot](https://github.com/YourUsername/E-commerce-Superstore-BI-Dashboard/raw/main/images/superstore_dashboard.png)

## 💡 Key Business Insights (Corrected)

The analysis was synthesized to provide three actionable insights based on the visual data:

1.  **Revenue Peak:** Sales follow a clear seasonal trend, peaking significantly in **Q4 (November and December)** and dropping sharply in January.
2.  **Top Performer:** The **Technology** category generates the highest overall Net Sales and is highly efficient. This category should be scaled aggressively.
3.  **Profitability Drag:** The **Central Region** consistently shows the lowest **Profit Margin %**, indicating systemic issues with high costs (likely shipping/logistics) or aggressive discounting, despite being a decent revenue source.

## 📈 Actionable Recommendations

Based on the validated insights, the following strategies are advised:

1.  **Targeted Q4 Campaign:** Allocate the majority of the annual marketing budget (e.g., 60%) to campaigns running from **October to December** to maximize conversion during the predictable holiday sales peak.
2.  **Central Region Cost Review:** Initiate a detailed operational audit of **logistics and discount strategies** within the Central Region to identify and cut unnecessary overhead, aiming to bring its Profit Margin % in line with the West Region.
3.  **Furniture Optimization:** While Furniture is a revenue driver, a detailed look at its sub-categories showed high discount rates and frequent returns. Recommend implementing a minimum profit threshold for all Furniture SKUs (Stock Keeping Units) and **aggressively repricing low-margin items** like certain 'Tables' and 'Bookcases.'
