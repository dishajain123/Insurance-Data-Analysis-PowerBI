# 📊 Insurance Data Analysis – Power BI Project

This project showcases an interactive Power BI dashboard built using SQL Server and Power BI to analyze insurance data. It includes various insights such as claim status, customer demographics, policy types, premium and coverage amounts, and more.

---

## ✅ Tools Used
- Microsoft SQL Server (for data import and querying)
- Power BI Desktop (for data visualization and dashboard creation)
- Flat File (CSV Dataset)

---

## 📁 Project Overview

1. **Database Setup (SQL Server):**
   - Created a database: `InsuranceDB`
   - Imported flat file (CSV) into SQL Server using Import Wizard
   - Modified `PolicyNumber` column to `VARCHAR(MAX)`
   - Executed queries to verify data import

2. **Power BI Setup:**
   - Connected Power BI to SQL Server database
   - Transformed and cleaned data using Power Query
   - Changed data types, created conditional columns (Age Group, Active/Inactive)

3. **Visuals Created in Power BI:**
   - **Slicers:** Policy Number, Claim Number, Customer ID (Dropdown Style)
   - **Cards:** Premium Amount, Coverage Amount, Claim Amount
   - **Multi-row Card:** Gender-wise customer count
   - **Ribbon Chart:** Claim Status distribution
   - **Bar Chart:** Policy Type vs Premium Amount
   - **Line Chart:** Age Group vs Claim Amount
   - **Donut Chart:** Active vs Inactive Policies
   - **Matrix Table:** Policy Type vs Claim Status vs Coverage Amount
   - **Drill-through Table (Page 2):** Detailed policy type data

---

## 🔄 Key Data Transformations
- Converted `Age` to Whole Number
- Created **Age Group** column using Conditional Column logic:
  - Age ≤ 24 → *Young Adult*
  - Age ≤ 60 → *Adult*
  - Else → *Elder*
- Created **Active/Inactive** column based on policy end date

---

## 📸 Dashboard Screenshots

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/abcbb81b-a5bb-480d-b385-afe87415d83c" alt="Dashboard View 1" width="400"/><br/>
      <sub><b>Dashboard Page 1</b></sub>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/90bcc184-cced-4204-bae9-b1029a54fd52" alt="Dashboard View 2" width="400"/><br/>
      <sub><b>Dashboard Page 2</b></sub>
    </td>
  </tr>
</table>



