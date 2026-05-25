# Sales Analysis Dashboard 📊

## Project Overview
This project is a **Sales Analytics Dashboard** created using **Power BI** to analyze sales performance, regional trends, and profitability using the Superstore dataset.

The dashboard helps businesses understand:
- Sales performance trends
- Regional profitability
- Product category performance
- Monthly sales growth
- Profit analysis

---

# Dashboard Preview

![Dashboard Preview](https://github.com/revanthk58/Sales_Analysis_Assignment/blob/main/Screenshots/Screenshot%202026-05-25%20153933.png)

---

# Tools & Technologies Used

- Power BI
- Excel / CSV Dataset
- SQL
- Python
- Data Cleaning
- Data Visualization

---

# Key KPIs & Visualizations

## 1. KPI Metrics Dashboard

### Metrics:
- Total Sales → **632.63K**
- Total Profit → **85.80K**
- Total Orders → **1,358**
- Profit Margin → **0.14**

### Insights:
- Business generated strong overall sales revenue.
- Profit margin indicates stable profitability.
- Order volume remained consistent throughout the year.

---

## 2. Sum of Sales by Month

### Insights:
- Sales fluctuate across different months.
- Peak sales observed during seasonal business periods.
- Monthly trend analysis helps identify business growth patterns.

### Visualization Used:
- Line Chart

![Sales Trend](https://github.com/revanthk58/Sales_Analysis_Assignment/blob/main/Screenshots/Screenshot%202026-05-25%20154025.png)

---

## 3. Sum of Profit by Month

### Insights:
- Profitability changes significantly month-to-month.
- Some months generate higher profit despite lower sales.
- Useful for tracking business performance efficiency.

### Visualization Used:
- Area Chart

![Profit Trend](https://github.com/revanthk58/Sales_Analysis_Assignment/blob/main/Screenshots/Screenshot%202026-05-25%20154115.png)

---

## 4. Average of Sales by Category

### Insights:
- Technology category has the highest average sales.
- Furniture and Office Supplies contribute consistently.
- Category analysis helps identify high-performing products.

### Visualization Used:
- Donut Chart

![Category Analysis](https://github.com/revanthk58/Sales_Analysis_Assignment/blob/main/Screenshots/Screenshot%202026-05-25%20154155.png)

---

## 5. Sum of Profit by Region

### Insights:
- East and West regions generate the highest profits.
- South region contributes lower profitability.
- Regional analysis helps identify strong markets.

### Visualization Used:
- Clustered Bar Chart

![Regional Profit](https://github.com/revanthk58/Sales_Analysis_Assignment/blob/main/Screenshots/Screenshot%202026-05-25%20154211.png)

---

## 6. Sum of Sales by Customer Name

### Insights:
- Top customers contribute a major portion of total revenue.
- Customer analysis helps identify valuable business clients.
- Useful for customer retention strategies.

### Visualization Used:
- Horizontal Bar Chart

![Customer Sales](https://github.com/revanthk58/Sales_Analysis_Assignment/blob/main/Screenshots/Screenshot%202026-05-25%20154230.png)

---

## 7. Count of Sub-Category by Month and Region

### Insights:
- Product demand changes across regions and months.
- Some regions show stronger category performance.
- Helps businesses optimize inventory planning.

### Visualization Used:
- Multi-Line Chart

![Sub Category Analysis](https://github.com/revanthk58/Sales_Analysis_Assignment/blob/main/Screenshots/Screenshot%202026-05-25%20154136.png)

---

## 8. Interactive Dashboard Filters

### Available Filters:
- Region
- Order Year

### Insights:
- Users can dynamically filter dashboard visuals.
- Improves interactive data exploration.

### Visualization Used:
- Slicers

---

# Business Insights

- East and West regions generated the highest profits.
- Technology category showed strong sales performance.
- Monthly sales and profit trends varied significantly.
- Top customers contributed heavily to overall revenue.
- Regional performance analysis highlights profitable markets.

---

# Learning Outcomes

Through this project, I learned:
- Data cleaning and transformation
- Building interactive Power BI dashboards
- Creating business-focused visualizations
- DAX calculations and measures
- Data storytelling and reporting
- Dashboard design best practices

---

# DAX Calculations Used

## Profit Margin

```DAX
Profit_Measure = DIVIDE(SUM(Orders[Profit]), SUM(Orders[Sales]))
```

## Order Year Column

```DAX
Order_year = YEAR(Orders[Order Date])
```

---

# Future Improvements

- Add sales forecasting
- Create customer segmentation analysis
- Integrate SQL database
- Build real-time dashboards
- Add advanced DAX measures

---

# How to Run the Project

1. Download the `.pbix` file
2. Open using **Power BI Desktop**
3. Refresh dataset if needed
4. Explore interactive visuals and slicers

---

# Repository Structure

```text
├── Superstore_sales_Analysis.csv
├── Screenshots
├── Sales_Analysis.pdf
├── README.md
└── Sales_Analysis.pbix
```

---

# Author

## Kanna Revanth Kumar

- Data Analytics Enthusiast
- Power BI Developer
- Python & SQL Learner

---

# Connect With Me

- GitHub: https://github.com/
- LinkedIn: https://www.linkedin.com/

---

# Star This Repository ⭐

If you found this project useful, give it a ⭐ on GitHub.
