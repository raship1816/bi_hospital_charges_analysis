# bi_hospital_charges_analysis


📊 Overview

This Power BI dashboard analyzes hospital charges, Medicare payments, and discharges across different Diagnosis-Related Groups (DRGs). The goal is to identify cost trends, expensive procedures, and state-wise hospital billing variations.

📂 Dataset

Columns:

DRG Definition

Provider ID

Provider Name

Provider State

Total Discharges

Average Covered Charges

Average Medicare Payments

Data Source: CMS (Centers for Medicare & Medicaid Services)


📈 Key Features

✅ KPI Cards: Total Discharges, Average Covered Charges, and Medicare Payments.
✅ Trend Analysis: Medicare Payments vs. Covered Charges across DRGs.
✅ Top 10 Expensive DRGs: Identifying high-cost medical procedures.
✅ State-wise Charges: Table to compare provider charges across states.
✅ Dynamic Filters: Users can filter by State & DRG Definition.
✅ DAX Measures Used:

Total Covered Charges = SUM('hospital-charges'[Average Covered Charges])

Total Medicare Payments = SUM('hospital-charges'[Average Medicare Payments])



📌 Skills Demonstrated

✔️ Power BI (Data Visualization, Dashboard Design, Report Optimization)
✔️ DAX (Calculated Measures, Aggregations)
✔️ Data Cleaning & Transformation (Power Query)
✔️ Interactive Reporting (Filters, Drill-through, User Experience)

🚀 How to Use

Open the Power BI file (.pbix).

Explore different filters and visuals.

Analyze trends and insights for hospital billing and Medicare costs.

📢 About the Project

This project provides a comprehensive view of hospital billing trends, enabling stakeholders to make data-driven decisions regarding healthcare costs and reimbursements. The interactive nature of the dashboard allows for deep exploration of high-cost medical procedures across different states.
