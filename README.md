# SUPERSTORE-PROFIT-REPORT-DASHBOARD

# 🏬 Superstore Profit Report Dashboard | Power BI

## 📌 Project Overview

The **Superstore Profit Report Dashboard** is an interactive Business Intelligence project developed using **Power BI** to analyze retail sales and profitability across the United States. The dashboard provides valuable insights into sales, profit, shipping performance, customer segments, and regional trends through dynamic visualizations and KPI metrics.

This project demonstrates skills in data cleaning, data modeling, DAX, and dashboard development to support data-driven business decisions.

---

# 🎯 Objectives

- Analyze overall sales and profit performance.
- Monitor key business KPIs.
- Identify top-performing product categories and sub-categories.
- Compare sales and profit performance across regions and states.
- Analyze customer segments and shipping preferences.
- Track product returns and their impact on profitability.
- Build an interactive dashboard for business reporting.

---

# 📂 Dataset Information

The project uses a multi-sheet Excel workbook containing order, customer, and returns data.

### Order sheet includes:

- Row ID, Order ID, Order Date, Ship Date, Ship Mode
- Customer ID, Customer Name, Segment
- Country, City, State, Postal Code, Region
- Product ID, Category, Sub-Category, Product Name
- Sales, Quantity, Discount, Profit

### People sheet includes:

- Person (Regional Manager)
- Region

### Returns sheet includes:

- Returned (Yes/No)
- Order ID

**Categories:** Furniture, Office Supplies, Technology
**Segments:** Consumer, Corporate, Home Office
**Ship Modes:** Standard Class, Second Class, First Class, Same Day
**Regions:** East, West, Central, South
**Records:** ~9,800 order line items across ~4,900 unique orders
**Time Period:** January 2014 – December 2017
**Geography:** United States (State & City level)

**Dataset Format:** Excel (.xlsx)

---

# 🛠️ Tools & Technologies

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Git & GitHub

---

# 🔄 Project Workflow

1. Import the Order, People, and Returns sheets into Power BI.
2. Clean and transform data using Power Query.
3. Create relationships between Order, People (by Region), and Returns (by Order ID).
4. Develop DAX measures for KPI calculations.
5. Design interactive dashboard visuals.
6. Analyze sales, profit, and return trends.
7. Generate business insights and recommendations.

---

# 📊 Dashboard Features

- KPI Cards
  - Total Sales
  - Total Profit
  - Profit Margin
  - Total Orders
  - Total Returns
- Sales & Profit by Category / Sub-Category
- Sales & Profit by Region / State
- Sales by Customer Segment
- Sales by Ship Mode
- Returns Analysis
- Monthly / Yearly Sales Trend
- Interactive Filters & Slicers

---

# ❓ Key Business Questions

- What is the total sales revenue and profit?
- Which product categories and sub-categories are most/least profitable?
- Which regions and states generate the highest sales and profit?
- How does customer segment influence sales performance?
- Which shipping mode is most commonly used?
- What percentage of orders are returned, and how does that affect profit?
- What are the sales and profit trends over the years?

---

# 📈 Key KPIs

- Total Sales
- Total Profit
- Profit Margin (%)
- Total Orders
- Total Returns
- Average Discount

---

# 💡 Key Insights

- Identified top-performing and loss-making product categories and sub-categories.
- Compared sales and profit performance across regions and states.
- Analyzed the impact of discounts on overall profitability.
- Evaluated customer segment contribution to total revenue.
- Tracked sales and profit trends from 2014 to 2017.
- Assessed the effect of returns on net profitability.

---

# 📊 Business Recommendations

- Reduce discounting on low-margin sub-categories to protect profit.
- Focus expansion and marketing in high-performing regions and states.
- Review and address product lines with high return rates.
- Promote high-margin categories to Corporate and Home Office segments.
- Optimize shipping mode offerings based on customer preference and cost.
- Use dashboard insights to support inventory and pricing decisions.

---


# 📁 Folder Structure

```text
Superstore-Profit-Report-Dashboard/
│
├── Dataset/
│   └── SALES_DATA_FINAL_DATA.xlsx
│
├── PowerBI/
│   └── SUPERSTORE_PROFIT_REPORT_DASHBOARD.pbix
│
├── README.md
└── LICENSE
```

---

# ▶️ How to Run the Project

1. Clone this repository.

```bash
git clone https://github.com/bhaktig0210/Superstore-Profit-Report-Dashboard.git
```

2. Open **Power BI Desktop**.

3. Open the `SUPERSTORE_PROFIT_REPORT_DASHBOARD.pbix` file.

4. If prompted, reconnect the dataset (`SALES_DATA_FINAL_DATA.xlsx`).

5. Refresh the data.

6. Explore the dashboard using interactive filters and slicers.

---

# 🚀 Future Improvements

- Connect the dashboard to a live SQL database.
- Automate data refresh using Power BI Service.
- Add sales forecasting using machine learning models.
- Include customer segmentation and cohort analysis.
- Publish the dashboard for online access.

---

# 👩‍💻 Author

**Bhakti Khandu Ghogare**

Aspiring Data Analyst skilled in **SQL, Power BI, Python, Excel, PostgreSQL, and Data Visualization**.

- **GitHub:** https://github.com/bhaktig0210
- **LinkedIn:** www.linkedin.com/in/bhakti0210
