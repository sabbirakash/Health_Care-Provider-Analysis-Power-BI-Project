# 🏥 Healthcare Provider Dashboard | Power BI

> An interactive Healthcare Analytics Dashboard built in **Microsoft Power BI** to analyze hospital billing, treatment costs, insurance coverage, departmental performance, and patient service distribution. The dashboard enables healthcare providers to monitor financial KPIs, identify high-revenue departments, and explore operational performance through dynamic visualizations and DAX-driven calculations.

---

<p align="center">
  <img src="https://github.com/sabbirakash/Health_Care-Provider-Analysis-Power-BI-Project/blob/main/Images/Health%20Care%20Provider%20Analysis%20Banner.png" width="100%">
</p>

---

## 📌 Project Overview

Healthcare organizations generate large volumes of operational and financial data every day. Converting this information into actionable insights is essential for improving financial performance and decision-making.

This project presents an interactive Power BI dashboard that analyzes healthcare billing and cost data. It provides a comprehensive view of billing amount, treatment expenses, medication costs, insurance coverage, room charges, and patient payment responsibilities while allowing users to explore data by procedure, department, service type, city, and state.

---

## 🎯 Project Objectives

- Analyze overall healthcare billing performance
- Monitor treatment, medication, and room costs
- Compare insurance coverage against patient out-of-pocket expenses
- Identify top-performing medical departments
- Evaluate billing contribution by medical procedures
- Analyze service type distribution (Emergency, Inpatient, Outpatient)
- Enable geographical analysis using City and State
- Build an interactive dashboard using DAX measures and dynamic filtering

---

# 📊 Dashboard Preview

<p align="center">
<img src="https://github.com/sabbirakash/Health_Care-Provider-Analysis-Power-BI-Project/blob/main/Images/Screenshot%20Dashboard%20Light.png" width="100%">
</p>

<p align="center">
<img src="https://github.com/sabbirakash/Health_Care-Provider-Analysis-Power-BI-Project/blob/main/Images/Screenshot%20Dashboard%20Dark.png" width="100%">
</p>

---

# 📁 Dataset Information

The dataset contains healthcare billing and operational records including:

- Patient ID
- Procedure Performed
- Department
- Treatment Cost
- Medication Cost
- Room Charges
- Length of Stay
- Insurance Coverage
- Patient Satisfaction Score
- City
- State
- Service Type
- Visit Date

---

# 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Bing Maps
- Interactive Slicers

---

# 📐 Data Modeling

The project follows a star-schema style data model where the fact table is connected with supporting dimension tables.

Main tables include:

- Visits
- Departments
- Procedures
- Cities
- Date Table

A custom Date Table was created using **CALENDARAUTO()** with additional Year, Month, Quarter, Weekday and Week Type columns to support time intelligence analysis. :contentReference[oaicite:0]{index=0}

---

# ⚙️ DAX Measures

Several custom DAX measures were created including:

### Financial Measures

- Total Billing Amount
- Total Treatment Cost
- Total Medication Cost
- Total Room Charges
- Total Insurance Coverage
- Out-of-Pocket Amount

### Average Measures

- Average Billing Amount per Visit
- Average Treatment Cost
- Average Medication Cost
- Average Room Cost
- Average Insurance Coverage
- Average Stay Duration
- Average Patient Satisfaction Score

### Analytical Measures

- Procedure Contribution %
- Department Contribution %
- Dynamic City / State Switch
- Active Department Selection

These calculations were implemented using functions such as:

- SUM()
- SUMX()
- DIVIDE()
- CALCULATE()
- ALL()
- SELECTEDVALUE()
- CALENDARAUTO()

:contentReference[oaicite:1]{index=1}

---

# 📈 Dashboard Features

### Executive KPI Cards

- Total Billing Amount
- Medication Cost
- Treatment Cost
- Room Charges
- Insurance Coverage
- Out-of-Pocket Amount
- Average Billing per Visit
- Average Medication Cost
- Average Treatment Cost
- Average Room Cost

---

### Interactive Visualizations

- Billing Amount by Procedure
- Billing Amount by Department
- Billing Distribution by Service Type
- Geographic Billing Analysis
- Dynamic City / State Switch
- Interactive Filters

---

# 🔍 Business Insights

### 💰 Financial Performance

- Generated over **$3.4M** in total billing.
- Insurance covered approximately **$2.2M**, leaving patients responsible for nearly **$1.1M**.

---

### 🏥 Department Analysis

- Cardiology generated the highest billing revenue.
- Orthopedics and General Surgery followed closely behind.
- Pediatrics contributed the smallest share of total billing.

---

### 🩺 Procedure Analysis

- X-Ray contributed the highest billing amount.
- CT Scan ranked second.
- Blood Tests generated the lowest billing among the analyzed procedures.

---

### 🚑 Service Type Analysis

- Outpatient services represented the largest billing share across most procedures.
- Emergency and Inpatient services contributed smaller but significant portions depending on the procedure.

---

### 🌍 Geographic Analysis

- Users can dynamically switch between **City** and **State** to identify high-revenue healthcare locations.

---

# 🎨 Dashboard Highlights

- Professional Light Theme
- Dark Mode Version
- Responsive Layout
- Interactive Slicers
- Dynamic Location Switch
- KPI Cards
- Geographic Map Visualization
- Clean Executive Dashboard Design

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Modeling
- Power Query
- DAX Programming
- KPI Development
- Financial Analytics
- Healthcare Analytics
- Dashboard Design
- Interactive Reporting
- Business Intelligence

---

# 📂 Repository Structure

```
Healthcare-Provider-Dashboard/
│
├── Dashboard/
│   └── Healthcare Provider Dashboard.pbix
│
├── Dataset/
│   └── Healthcare Dataset.xlsx
│
├── Images/
│   ├── Healthcare Provider Dashboard.png
│   └── Dashboard Banner.png
│
├── Documents/
│   ├── Dashboard Requirements.pdf
│   ├── Dashboard Summary.pdf
│   └── DAX & KPI's.pdf
│
└── README.md
```

---

# 📌 Project Highlights

✔ Interactive Healthcare Dashboard

✔ Advanced DAX Calculations

✔ Dynamic KPI Cards

✔ Financial Performance Analysis

✔ Department & Procedure Analysis

✔ Geographic Visualization

✔ Responsive Dashboard Design

✔ Light & Dark Theme Support

---

# 📚 Key Learnings

Throughout this project, I strengthened my skills in:

- Creating efficient DAX measures
- Building reusable Date Tables
- Designing interactive Power BI dashboards
- Developing healthcare-specific KPIs
- Implementing dynamic filtering techniques
- Applying business intelligence concepts to healthcare financial data

---

# ✅ Conclusion

This project demonstrates how Power BI can transform healthcare operational data into meaningful business insights through interactive dashboards and advanced DAX calculations. By combining financial KPIs, departmental performance, procedural analysis, and geographic reporting, the dashboard provides healthcare providers with a centralized view of their operations, supporting faster decision-making and improved financial planning.

---

## 👨‍💻 Author

**Sabbir Uddin Akash**

- 💼 Aspiring Data Analyst
- 📊 Power BI | SQL | Excel | Python
- 🌐 GitHub: [SabbirAkash](https://github.com/sabbirakash)

If you found this project useful, consider giving it a ⭐.
