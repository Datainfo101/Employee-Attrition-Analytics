# HR Employee Attrition Analysis (Excel Dashboard)

This project provides a comprehensive analysis of employee attrition using Microsoft Excel. It uses structured datasets and pivot-based dashboards to explore key drivers of employee exit behavior and recommends HR interventions based on visual insights.

---

## Project Structure

📦 HR-Attrition-Excel-Analysis
│
├── 📊 Attrition_Pivot_HighRisk_Dataset.xlsx
├── 📈 Simple_Attrition_Risk_Model.xlsx
├── 🧾 Distance_Attrition_Analysis.xlsx
├── 📋 Attrition_Dashboard_Insights_Comments.xlsx
└── README.md

---

## 📌 Objectives

- Understand **which employee groups are at high risk** of attrition.
- Identify **top attrition factors** (e.g. overtime, distance, satisfaction).
- Build **interactive pivot dashboards** to visualize trends.
- Apply **conditional formatting** to highlight critical risk zones.
- Recommend **actionable HR interventions**.

---

## 🧪 Dataset Overview

- `Employee ID`
- `Age`
- `Department`
- `Distance From Home`
- `OverTime`
- `Job Satisfaction`
- `Environment Satisfaction`
- `Monthly Income`
- `Attrition` (Yes/No)

The dataset contains synthetic employee records used to simulate real-world HR attrition behavior.

---

## 📊 Key Features & Analysis

### ✅ 1. Distance from Home vs Attrition
- Grouped into distance bins
- Highlighted areas where attrition spikes beyond 20%

### ✅ 2. Job Satisfaction & Environment Satisfaction
- Conditional color scale used to emphasize low scores linked to high attrition

### ✅ 3. Relationship Satisfaction Impact
- Visualized satisfaction impact using color-coded scales

### ✅ 4. Attrition by Income Groups
- Used binning to group income
- Compared attrition trends across ranges

### ✅ 5. Correlation Analysis
- Numeric conversion and correlation matrix to identify key predictive factors

### ✅ 6. Risk Flag Modeling
- Used `IF()` + `AND()` logic to flag "High Risk" employees based on:
  - Age
  - Overtime
  - Distance
  - Satisfaction
  - Income

---

## 📈 Dashboard Highlights

The `Attrition_Dashboard_Insights_Comments.xlsx` contains:

- 📌 Insight boxes
- ✅ Intervention boxes
- 🔴 High attrition rates highlighted
- 📊 Pivot table visuals
- 🌡️ Suggestions for trend analysis

---

## 💡 Recommended HR Actions

- Retain young employees working overtime with flexible policies.
- Support long-commuting employees with hybrid work options.
- Prioritize employee satisfaction monitoring.
- Focus retention efforts on Sales & Customer-Facing roles.

---

## 🔧 Tools Used

- 📎 Microsoft Excel (Pivot Tables, Charts, Conditional Formatting, Formulas)
- 📊 Visual Charts: Line, Column, KPI Cards
- 🧠 Logical Functions: `IF()`, `AND()`, `COUNTIF()`, `CORREL()`

---

## 📬 Contact

> Created by [https://github.com/Datainfo101]  
> ✉️ For questions or collaboration, feel free to open an issue or connect.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
Would you like me to generate a LICENSE file or push this into a zip-ready README.md file for upload?
















