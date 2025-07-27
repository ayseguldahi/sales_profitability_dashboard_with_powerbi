## 📊 Sales & Profitability Dashboard with Power BI

This project presents an interactive dashboard built in **Power BI** to analyze and optimize sales and profitability performance across different segments and categories. The dashboard helps identify high-performing regions, track sales and profit trends over time, and evaluate the impact of discounting and shipping costs on profitability.

## 🔍 Project Objectives

- Analyze sales and profit performance across categories, sub-categories, regions, and customer segments.
- Compare key KPIs such as **Total Sales**, **Profit**, **Profit Ratio**, and **Discount Impact** using dynamic visualizations.
- Reveal trends and seasonality using **time series decomposition** and **trend analysis**.
- Provide stakeholders with actionable insights to optimize pricing and marketing strategy.

## 🛠 Key Features & Tools

- **Power BI** for dashboard design and data modeling.
- **DAX measures** for custom KPIs such as:
  - `Profit Ratio = DIVIDE(SUM(Profit), SUM(Sales))`
  - `Average Discount = AVERAGE(Discount)`
  - `YOY Sales Growth = (ThisYearSales - LastYearSales) / LastYearSales`
- **Interactive visuals** including:
  - Time-series line charts for Sales and Profit.
  - Bar/Column charts for Top 10 Sub-Categories.
  - Region-wise profitability maps.
  - Slicers and filters for dynamic segment analysis.
- **Custom Tooltips** and **Drill-through Pages** for detailed exploration.

## 📁 Project Structure

```
📂 sales_profitability_dashboard_with_powerbi/
│
├── 📄 Sales & Profitability Dashboard.pbix        # Power BI report file
├── 📄 Sales and Profitability Dashboard-Report.pdf # Summary report (PDF)
└── 📄 README.md                                    # This file
```

## 🧠 Insights Discovered

- **Technology** and **Office Supplies** showed higher profit margins.
- **Central** and **East** regions had more consistent profitability.
- Excessive discounting negatively impacted profit in **Furniture** sub-category.
- **Top Customers** were responsible for a significant share of total revenue.

## 📌 Requirements

- Power BI Desktop (latest version)
- Sample Superstore dataset (embedded in `.pbix`)

## 📬 Contact

Created by [Aysegul Dahi](https://github.com/ayseguldahi)  
For questions, feel free to reach out!

---
