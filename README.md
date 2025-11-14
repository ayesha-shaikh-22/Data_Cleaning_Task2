**README.md — Global Superstore Power BI Dashboard**

**By Ayesha Shaikh**


# 🚀 **Global Superstore – Power BI Data Analytics Project**

This project presents a complete **end-to-end data analytics solution** using Power BI.
It includes data cleaning, data modeling, DAX measure creation, and building interactive dashboards with business insights and recommendations.

The dataset used is **Global Superstore**, a retail sales dataset containing order-level data across various categories, sub-categories, regions, and customer segments.



# 📂 **Project Structure**


Professional title page with project name, analyst details, and report overview.


High-level KPIs & performance overview:

* Total Sales
* Total Profit
* Profit Margin
* Total Orders
* Average Order Value
* Monthly Sales Trend
* Sales vs Profit
* Sales by Region
* Sales by Category
* Year & Date Slicers


Deep-dive analytics with:

* Top 10 Products
* Sales & Profit by Segment
* Category → Sub-Category Drilldown
* Region vs Category Profit Heatmap
* YoY Sales Comparison
* Customer Performance Summary


Data-driven insights about:

* Sales trends
* Profit behavior
* Customer segment performance
* Category breakdown
* Regional highlights

Actionable strategies for:

* Sales Growth
* Profit Optimization
* Customer Retention
* Inventory & Operations Improvement

---

 **Data Cleaning (Power Query)**

Performed essential cleaning tasks:

* Changed data types
* Removed duplicate rows
* Handled missing values
* Added Year & Month columns
* Standardized column formats
* Created a separate **Date Table**
* Established key relationships

---

**Data Modeling**

A **star schema model** was created with:

* **Fact Table:** Orders
* **Dimension Table:** Date

Relationship:

```
DateTable[Date] (1) → Orders[Order Date] (*)
```

Marked DateTable as the official date table for time intelligence.


# 📊 **DAX Measures Created**

Key measures include:

* `Total Sales`
* `Total Profit`
* `Total Quantity`
* `Profit Margin %`
* `Average Order Value`
* `Total Orders`
* `Sales LY`
* `YoY Sales %`
* `Sales by Product`
* `Profit by Product`

These measures helped build interactive charts and KPIs.


 

**Key Insights From the Dashboard**

* **Technology** is the highest-performing category.
* The **Consumer Segment** generates the most sales.
* **Q3 & Q4** show the strongest seasonal performance.
* **Central Region** contributes lower profit compared to West and East.
* Some high-selling products deliver **low margins** → pricing strategy opportunities.


**Business Recommendations**

* Invest more in high-profit categories like Technology.
* Improve regional strategies in Central and East regions.
* Reduce discounting in low-margin Furniture items.
* Launch loyalty programs for Consumer segment.
* Optimize inventory for peak demand months .


**Tools Used**

* **Power BI Desktop**
* Power Query (M Language)
* DAX (Data Analysis Expressions)
* Data Modeling Techniques
* Visualization & UX best practices


**About the Analyst**

**Ayesha Shaikh**
Data Analyst | Power BI | Python | SQL | Excel


**How to Use This Report**

1. Download the `.pbix` file from this repository.
2. Open using **Power BI Desktop**.
3. Navigate through the pages using tabs at the bottom.
4. Use slicers to explore data by year, date, region, and category.

**Dataset**

Global Superstore Dataset 

**Conclusion**

This project demonstrates a full analytical workflow — from data preparation to insight generation and storytelling. The interactive dashboards provide valuable business intelligence and help stakeholders make data-driven decisions.

