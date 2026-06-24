# Business-Intelligence-Workforce-Dashboard-using-Power-BI

## 📊 Project Overview
This project focuses on analyzing **HR attendance data** using **Microsoft Power BI** to uncover insights related to employee attendance, work mode preferences (work from home vs. office), and leave patterns.  
The dashboard enables HR stakeholders to monitor workforce behavior and make **data-driven decisions** for better resource planning and policy evaluation.


## 🎯 Business Problem & Objectives
Organizations need clear visibility into employee attendance and work patterns to optimize productivity and workforce planning.

### Objectives:
- Analyze overall **employee attendance trends**
- Identify **WFH vs Office** work preferences
- Measure **leave percentages**, including sick leaves
- Provide interactive and intuitive HR dashboards for decision-making

## 📁 Dataset Information
- **Source:** Excel files provided by HR executives  
- **Time Period:** 2022–2023  
- **Data Type:** Attendance & work mode data (masked for privacy)

### Key Columns:
- Employee ID  
- Attendance Date  
- Attendance Status  
- Work Mode (WFH / Office)  
- Leave Type  

> ⚠️ Note: The dataset is anonymized and used only for learning and demonstration purposes.

## 🧹 Data Cleaning & Transformation (Power Query)
Data preparation was performed using **Power Query**, including:
- Removing duplicate records
- Handling missing and invalid values
- Standardizing date and categorical fields
- Creating calculated columns for attendance and leave analysis
- Structuring data for efficient reporting
- 
## 🧱 Data Model Design
- Designed a **clean and optimized data model**
- Implemented logical relationships between attendance data and date attributes
- Ensured proper **cardinality and filtering** for accurate analysis
- Followed best practices to support scalable analytics

## 📐 DAX Measures & KPIs
Created custom **DAX measures** to support HR insights, including:
- Attendance Percentage
- Work From Home (WFH) Percentage
- Sick Leave Percentage
- Total Working Days
- Monthly and trend-based calculations

**DAX concepts used:**  
`CALCULATE`, `FILTER`, `DIVIDE`, `SUM`, `COUNT`, Date intelligence functions

## 📊 Dashboard Features & Visuals
The Power BI dashboard includes:
- **KPI cards** for attendance, WFH, and leave metrics
- **Line charts** to track monthly attendance trends
- **Bar/column charts** for work mode comparison
- **Slicers** for month and date-level analysis
- Interactive drill-down and filtering for exploration

## 🔍 Key Insights & Findings
- Attendance trends vary significantly across months
- WFH preference shows noticeable patterns over time
- Sick leave percentage spikes during specific periods
- The dashboard helps identify attendance behavior that can impact workforce planning

## 🛠 Tools & Technologies Used

| Tool | Purpose |
|----|----|
| Power BI Desktop | Dashboard development & visualization |
| Power Query | Data cleaning & transformation |
| DAX | KPI calculations & business logic |
| Microsoft Excel | Raw HR attendance data |
