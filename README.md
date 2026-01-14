# Retail Sales Analysis | Power BI • SQL • Excel

## 📌 Overview  
This repository contains a full retail business performance analysis using a combination of Power BI, SQL, Excel, and Python. The project uncovers key sales and profitability insights for data-driven decision-making.

---

## 🧰 Tools & Techniques
- **Power BI** – Interactive dashboard & DAX measures  
- **SQL** – Advanced analysis (aggregations, window functions, subqueries)  
- **Excel** – Data cleaning and PivotTable analysis  
- **Python** – Exploratory data analysis (Jupyter Notebook)  
- **Gamma AI** – Report documentation

---

## 📁 Repository Structure

```
Business-Performance-Analysis/
│
├── README.md
├── Dashboard/
│   ├── Retail_Sales_Dashboard.pbix
│   ├── dashboard_overview.png
│   ├── kpis.png
│   ├── top_5_products.png
│
├── Report/
│   └── Retail_Sales_Analysis_Report.pdf
│
├── Data/
│   └── Superstore_Data.csv
│
└── SQL_Queries/
    └── retail_analysis.sql
```

---

## 📊 Dashboard Highlights

### KPI Summary
https://github.com/Mehween-fatima/Business-Performance-Analysis/blob/main/Screenshot%202026-01-14%20045654.png

### Overall Dashboard
https://github.com/Mehween-fatima/Business-Performance-Analysis/blob/main/Screenshot%202026-01-14%20045527.png

### Top 5 Products by Profit
https://github.com/Mehween-fatima/Business-Performance-Analysis/blob/main/Screenshot%202026-01-14%20045720.png


---

## 📈 Key Insights

- Strong sales do not always translate to high profit across categories.
- Some states show high revenue but low or negative profit, indicating pricing or cost issues.
- High discount levels correlate with reduced profit margins.
- Seasonal trends in sales can guide future planning.

---

## 📌 Business Recommendations

- Focus marketing and inventory on high-margin products.
- Reassess pricing strategy for low-profit regions.
- Reduce excessive discounts on low profitability categories.
- Use seasonal trends to plan promotions and stock.

---

## 🧮 Example DAX Measures

```DAX
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
```

---

## 🔗 Resources

- **Power BI Dashboard**: `Dashboard/Retail_Sales_Dashboard.pbix`
- **Dataset**: `Data/Superstore_Data.csv`
- **SQL Queries**: https://github.com/Mehween-fatima/Business-Performance-Analysis/blob/main/Retail_Business_Analysis%20(2).ipynb
- **Project Report**: https://github.com/Mehween-fatima/Business-Performance-Analysis/blob/main/Business-Performance-Analysis-Report.pdf

---

## 👤 Author

**Mehween Fatima**  
Aspiring Data Analyst  
LinkedIn: https://www.linkedin.com/in/mehween-fatima-1955673a1  
GitHub: https://github.com/Mehween-fatima



