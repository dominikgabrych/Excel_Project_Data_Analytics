# 🧮 Data Science Salary Calculator Dashboard

An interactive Excel dashboard built to explore salary data across job roles, countries, job types, and platforms in the data science domain. Fully dynamic and designed for recruiters and analysts to quickly extract insights.

---

## 🚀 What It Does

- Displays **median salary**, **job count**, and **top job platform** based on user selection
- Visualizes salary distribution by **job title** and **job type**
- Maps **country-level salary medians** globally
- Highlights the **most common platform** for job listings per filter

![dashboardgif](https://github.com/user-attachments/assets/2024c529-b55f-4e36-a1b7-a3ed5c5a2c11)

---

## 🛠️ Skills & Techniques Demonstrated

### 🧩 Data Preparation
- Extracted and sorted **unique job titles**, **countries**, **job types**, and **platforms** using:
  - `UNIQUE`, `SORT`, `FILTER`, `ISNUMBER`
- Cleaned and validated data with **data validation lists** for full interactivity

![Zrzut ekranu 2025-07-04 225938](https://github.com/user-attachments/assets/7ad5b17a-43a0-4b50-afaa-f3b5e9b0de94)

### 📊 Dynamic Metrics
- Used **array formulas** with `IF`, `SEARCH`, and `MEDIAN` to calculate salary based on:
  - Job title  
  - Country  
  - Job type (Full-time, Part-time, Contract, etc.)
- Filtered non-numeric values to prevent errors in charts and dropdowns

![Zrzut ekranu 2025-07-04 172814](https://github.com/user-attachments/assets/5b953ed8-9b0c-4f6a-afea-16d1abc3fea6)

### 📈 Visualization Logic
- Implemented **conditional bar charts** to highlight selected job titles
- Created **map chart** with dynamic data for country salary medians
- Used `NA()` logic to toggle visibility in charts dynamically

![Zrzut ekranu 2025-07-04 175923](https://github.com/user-attachments/assets/6182e93d-ae19-47d6-a94b-36c903991087)

### 🔎 Lookup & Aggregation
- Applied `XLOOKUP` and `COUNTIFS` to display:
  - Selected job’s salary
  - Job count based on multiple filters
  - Most frequent job platform

![Zrzut ekranu 2025-07-04 173356](https://github.com/user-attachments/assets/96fd26ec-078f-4e34-bed8-ffac17df261a)

### 🧼 UX & Presentation
- Used:
  - **Clean layout** with KPIs (Median, Platform, Job Count)
  - **Dynamic text display**
  - **Conditional formatting**
- Removed unnecessary labels (e.g., stripping "via " from platforms) for clarity

