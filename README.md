# 🏥 Healthcare Analytics Dashboard 

## 📌 Project Objective
The objective of this project is to design an **interactive Healthcare Analytics Dashboard** that helps stakeholders analyze **patient trends, hospital performance, medical conditions, and billing patterns** over time.  
The dashboard enables quick decision-making by transforming raw healthcare data into **clear, visual, and actionable insights**.

---

## ❗ Business Problem Statement
Healthcare organizations manage large volumes of patient and financial data, making it challenging to:

- Track patient volume across multiple hospitals
- Identify the most common medical conditions
- Understand demographic patterns affecting admissions
- Monitor billing trends and insurance dependency
- Analyze hospital efficiency using length of stay metrics
- Quickly reset filters and navigate reports during analysis

This dashboard addresses these challenges by providing a **centralized, interactive, and user-friendly analytics solution**.

---

## 📊 Dashboard Pages Overview

### 🔹 1. Overview Page
The **Overview** page provides a high-level summary of key healthcare KPIs and performance metrics.

**Key KPIs and Visuals:**
- Total Patients
- Total Billing Amount
- Average Length of Stay
- Most Common Medical Condition
- Patients by Hospital
- Patients by Gender
- Patients Trend by Month / Quarter / Year (Field Parameter)
- Hospital vs Medical Condition heatmap table

**Features Implemented:**
- Month and Year slicers for time-based filtering
- Field Parameter to dynamically switch between Month, Quarter, and Year in the trend line chart
- Heatmap-style table showing hospitals vs medical conditions
- Page navigation buttons for Overview, Demographics, and Insights pages
- Clear button implemented using a bookmark to reset all slicers and visual selections

---

### 🔹 2. Demographics Page
The **Demographics** page focuses on patient distribution and characteristics.

**Visuals Included:**
- Patients by Age Group
- Patients by Age Group and Gender
- State-wise patient distribution using a map visual
- Age band analysis
- Medical condition-based filtering

**Interactivity:**
- Slicers for Year, Month, and Medical Condition
- Cross-filtering enabled across visuals
- Drill-down and hover interactions for deeper analysis

---

### 🔹 3. Insights Page
The **Insights** page provides deeper analytical views related to billing and treatment patterns.

**Key Visuals:**
- Billing by Month
- Billing by Medical Condition
- Billing by Insurance Provider
- Medical Condition vs Medication heatmap table

This page helps identify:
- High-revenue medical conditions
- Insurance provider contribution to billing
- Medication usage patterns across medical conditions

---

## 🛠️ Power BI Features Used
- DAX Measures (KPIs, averages, YoY calculations)
- Calculated Columns (Length of Stay calculation)
- Bookmarks (Clear / Reset functionality)
- Page Navigation buttons
- Field Parameters for dynamic time-based analysis
- Slicers (Month, Year, Medical Condition)
- Conditional Formatting for heatmap tables
- Interactive cross-filtering
- Optimized data model using fact and dimension tables

---

## 📈 Key Insights Generated
- Hypertension is the most common medical condition across hospitals
- Certain hospitals contribute significantly more to patient admissions
- Middle-age groups (30–59) show the highest patient volume
- Billing trends vary across months, indicating seasonality
- Insurance providers play a major role in total billing contribution

---

## 🧰 Tools & Technologies
- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Data Modeling
- GitHub for version control and documentation

---

## 🚀 How to Use the Dashboard
1. Use Month and Year slicers to filter the data
2. Navigate between pages using Page Navigation buttons
3. Click the Clear button to reset all filters and selections
4. Interact with visuals to apply cross-filtering
5. Use the Field Parameter to switch between Month, Quarter, and Year views

---

## 📌 Conclusion
This project demonstrates strong capabilities in **Power BI dashboard development, DAX, data modeling, and data storytelling**.  
The dashboard transforms complex healthcare datasets into meaningful insights through **interactive visuals, clean design, and business-focused analytics**.
