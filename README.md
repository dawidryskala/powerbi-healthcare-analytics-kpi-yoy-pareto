# 🏥 Healthcare Analytics Dashboard

Welcome to the **Healthcare Analytics Dashboard** repository! 🚀  
This project showcases a Power BI report designed for healthcare cost and performance analysis.  
The dashboard provides an interactive view of KPIs, Year-over-Year (YoY) comparisons, and Pareto insights, helping stakeholders make data-driven decisions.

[Healthcare Dashboard overview.pdf](https://github.com/user-attachments/files/21940228/Healthcare.Dashboard.overview.pdf)

## 📘 Project Overview

This project demonstrates:

- **Interactive Navigation** – Homepage with intuitive buttons linking to different analyses.
- **KPI Monitoring** – Six main KPIs with detailed breakdowns and optional dark mode.
- **YoY Comparison** – Dynamic view of current vs. previous year performance.
- **Pareto Analysis** – Identification of key drivers in healthcare billing.

Designed as a portfolio project, it highlights expertise in:

- Power BI Development  
- DAX Calculations  
- Healthcare Analytics  
- Data Visualization & UX  

---

## 🚀 Project Requirements

### 🎯 Objective
Build a healthcare analytics dashboard that empowers users to explore costs, trends, and drivers of healthcare expenses.

### 📌 Specifications
- **Data Sources:** Synthetic healthcare dataset with demographics, billing, and insurance.  
- **Metrics:** Billing Amount, Medical Cost, Treatment Cost, Insurance Coverage, Out-of-Pocket, Room Charges.  
- **User Experience:**
  - Navigation buttons  
  - Dark mode option  
  - Interactive filter pane  
  - Parameterized slicers  
- **Tools:** Power BI, DAX, Power Query  

---

## 🏗️ Dashboard Pages

### 1️⃣ Homepage
Navigation hub with three main buttons:

- KPI Overview  
- Actual vs Previous Year (YoY Analysis)  
- Pareto Analysis  

---<img width="1793" height="1024" alt="image" src="https://github.com/user-attachments/assets/8be1db5f-1e4e-4ebc-9f6d-84303491bd84" />

---

### 2️⃣ KPI Overview
Displays six main KPIs:

- Billing Amount  
- Medical Cost  
- Treatment Cost  
- Insurance Coverage  
- Out-of-Pocket  
- Room Charges  

**Detailed breakdowns for Billing Amount:**

- by Age Group  
- by Procedure  
- by Department  
- by Diagnosis & Service Type (100% stacked bar chart)  


<img width="1797" height="1025" alt="image" src="https://github.com/user-attachments/assets/7b8e35e5-8bb9-4788-acf0-b941c46f169b" />

Dark Mode version for low-light presentations.
<img width="1792" height="1023" alt="image" src="https://github.com/user-attachments/assets/b0a64191-1bc0-43f7-8fb9-54cbc58998bf" />

---

### 3️⃣ Actual vs Previous Year (YoY Analysis)
Compares current performance with the same period last year.

Each KPI shows:

- Current value  
- Previous year value  
- Difference (absolute & percentage)  

**Conditional formatting:**

- Costs ↑ = 🔴 (negative), Costs ↓ = 🟢 (positive)  
- Insurance Coverage ↑ = 🟢 (positive), ↓ = 🔴 (negative)  

**Interactivity:** Clicking a KPI updates charts & matrix dynamically.

<img width="1792" height="1023" alt="image" src="https://github.com/user-attachments/assets/5c2bb439-c058-4ef9-a11e-d6209336c0b2" />


---

### 4️⃣ Pareto Analysis
Focused on **Billing Amount by Age Group**.

**Pareto Chart (bar + cumulative line):**

- Bars = % of billing per age group  
- Line = cumulative % of billing  

**Interactive slider:** select cutoff (e.g., 40%) → highlights relevant age groups

**Matrix Table includes:**

- Age Group  
- Billing Amount  
- % of Grand Total  
- Cumulative Billing & %  

UX highlighting consistent with chart.

<img width="1792" height="1023" alt="image" src="https://github.com/user-attachments/assets/069fabf9-f2d5-431b-99d7-2c4923001478" />


---

## 🗂️ Data Model
The data model in Power BI includes:

- **Fact Table:** Billing & Costs  
- **Dimensions:** Patient, Procedure, Diagnosis, Department, Date, Insurance Provider  

<img width="1798" height="915" alt="image" src="https://github.com/user-attachments/assets/c71e0298-9c1d-4556-8798-1b951785933e" />


---

## 📄 Full Report Demo (PDF)
You can also explore the entire report walkthrough in a PDF file:

👉 *Download Healthcare Dashboard Demo (PDF)*  

---

## 🛡️ License
This project is licensed under the [MIT License].  
You are free to use, modify, and share this project with proper attribution.

---

## 🌟 About Me
Hi there! I'm **Dawid Ryskala** — a BI Developer and Data Analyst passionate about transforming raw data into actionable insights.  
I enjoy building interactive dashboards, designing DAX logic, and helping businesses make data-driven decisions.

📌 Connect with me on LinkedIn:  

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-Dawid%20Ryskala-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/dawidryskala/)

---

✅ Ten README jest gotowy do wrzucenia — wystarczy tylko podpiąć screeny i PDF.
