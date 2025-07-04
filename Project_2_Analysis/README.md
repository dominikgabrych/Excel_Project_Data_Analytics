# 📊 Skill vs Salary Dashboard (Excel BI Project)

An interactive Excel dashboard analyzing how technical skills impact salaries in the data industry. The project showcases data modeling, transformation, and visualization using Excel’s **Power Query**, **Power Pivot**, and advanced charting tools.

---

## 🚀 Project Summary

**Goal:**  
To understand which technical skills (e.g. Python, SQL, Power BI) are most associated with higher salaries across job roles and countries.

---

## 🛠️ Tools & Techniques Used

### 🔄 Power Query

![Zrzut ekranu 2025-07-04 230902](https://github.com/user-attachments/assets/0fe153e4-e978-4d94-b1c2-a78a8a2948e2)

Used to clean and transform raw data:

- **Removed nulls and irrelevant columns**
- **Pivoted/unpivoted columns** to reshape skill frequency tables
- **Standardized job titles** and country names
- **Merged queries** for skill ↔ salary matching
- Created **normalized tables** for Skills, Jobs, Countries

### 🧮 Power Pivot / Data Model

![Zrzut ekranu 2025-07-04 231021](https://github.com/user-attachments/assets/c09f26b5-50ec-49ad-9313-e3f8ada70fe6)

- Built **relationships** between job titles, skills, and salary tables
- Created **calculated columns** and **measures** using DAX:
  - Median salary by skill
  - Skill frequency by role
  - Median salary by country (US vs Non-US)

### 📊 Dashboard & Excel Visualizations

![Zrzut ekranu 2025-07-04 231045](https://github.com/user-attachments/assets/1c3a3f0d-e058-4a2d-bf74-86090e6015d0)

Structured into 4 dynamic summary views:

#### 1. **Skill Impact on Salary**
- Compared job roles based on:
  - Median Salary  
  - Average number of skills required
- Highlighted how roles with more skills often earn more

#### 2. **Median Salary by Country**
- Compared U.S. and non-U.S. salary medians
- Combined into a clean summary for global comparison

#### 3. **Skill Frequency**
- Displayed which tools/languages are most in-demand
- Used a horizontal bar chart for intuitive reading

#### 4. **Top Skills by Pay**
- Ranked skills by:
  - Median salary
  - Frequency in job postings
- Used bubble chart for impact visualization

---

## 🧰 Excel Features Used

- Power Query Editor
- Power Pivot Data Model
- PivotTables and PivotCharts
- Slicers and interactive filters
- DAX Measures (e.g., `MEDIANX`, `CALCULATE`, `FILTER`)
- Clean UX design for non-technical stakeholders

---

## 💡 Key Insights

- **Python**, **Tableau**, and **SQL** appear most frequently and correlate with higher salaries
- Roles like **Data Engineer** and **Senior Data Scientist** tend to require more skills and offer higher pay

---

## 📎 Use Cases

- Portfolio project for data analyst or BI roles  
- Can be adapted for:
  - HR/Recruiting analytics
  - Skill gap analysis
  - Salary benchmarking tools

---

> ✅ A no-code BI project demonstrating advanced Excel capabilities in business intelligence, suitable for recruiters, hiring managers, or stakeholders exploring the value of tech skills in compensation.

