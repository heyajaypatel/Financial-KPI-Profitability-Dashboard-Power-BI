# Financial KPI Monitoring & Profitability Dashboard | Power BI

## 🎯 Project Overview
This project is a high-level Business Intelligence solution designed for finance analysts and management teams to monitor a company’s financial health. It provides a single-view summary of critical metrics like Net Profit, Gross Margin, and Budget Variance, allowing leadership to move from descriptive reporting to data-driven strategic planning.

## 📊 Key Financial KPIs
* [cite_start]**Total Revenue:** Overall income generated from sales[cite: 499].
* [cite_start]**Gross Profit:** Revenue remaining after direct costs (COGS)[cite: 579].
* [cite_start]**Net Profit:** The final bottom-line profit after all operating expenses[cite: 580].
* [cite_start]**Profit Margin %:** Measures the efficiency of the business in converting revenue into profit[cite: 584].
* [cite_start]**Budget Variance:** Measures the difference between planned financial targets and actual performance[cite: 508, 588].

---

## 🛠️ Technical Workflow

### 1. Data Cleaning & Transformation (Power Query)
* [cite_start]**ETL Process:** Cleaned raw finance data by removing duplicates and ensuring 100% accuracy in currency and date formats[cite: 474, 475].
* [cite_start]**Calculated Columns:** Created custom logic to derive Profit directly from Revenue and Expense datasets[cite: 477].

### 2. Data Modeling (Star Schema)
* [cite_start]**Optimized Model:** Built a relational Star Schema connecting Fact tables (Revenue, Expenses) with Dimension tables (Date, Region, Department)[cite: 483, 495].
* [cite_start]**Time Intelligence:** Integrated a dedicated `DateTable` for year-over-year (YoY) growth and trend analysis[cite: 490, 491, 503].

### 3. DAX Analysis
* [cite_start]**Dynamic Measures:** Developed DAX formulas for Profit Margin %, Revenue Growth, and Budget Variance to allow real-time filtering[cite: 497, 510, 511].
* [cite_start]**Waterfall Logic:** Used waterfall visualization to break down the step-by-step reduction of revenue into net profit[cite: 601].

---

## 💡 Business Insights
* [cite_start]**Profitability Drivers:** Identified which product categories and regions yield the highest net margins[cite: 592].
* [cite_start]**Cost Control:** Pinpointed departments where expenses are exceeding budget targets[cite: 592, 593].
* [cite_start]**Forecasting:** Visualized 6-12 month revenue projections to identify seasonal patterns and future risks[cite: 528].

## 📸 Dashboard Preview
<img width="1920" height="1080" alt="Screenshot 2026-04-18 150508" src="https://github.com/user-attachments/assets/75a2e8a9-ea4e-4501-b01d-bf4d4c220e3b" />


## 🚀 How to Use
1.  Download the repository.
2.  Open the `.pbix` file in **Power BI Desktop**.
3.  Navigate to the `Data` folder to view the source CSV files.
4.  Use the **Slicers** (Region, Department, Time) to interact with the visual data.

---
**Target Job Roles:** Finance Analyst | FP&A Analyst | Business Analyst | Management Consultant.
