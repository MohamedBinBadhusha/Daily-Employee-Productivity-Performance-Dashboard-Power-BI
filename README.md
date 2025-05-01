# Daily-Employee-Productivity-Performance-Dashboard-Power-BI
This Power BI dashboard provides a comprehensive daily performance analysis for employees, enabling individual contributors and managers to monitor productivity, efficiency, and attendance patterns across teams.

# 📊 Daily Employee Productivity & Performance Dashboard (Power BI)

This project is a fully interactive Power BI dashboard that visualizes and analyzes **daily employee performance metrics** like Achieved Tasks, Efficiency, Quality Score, Time Utilization, and Availability.

Designed for operational teams, this dashboard provides individual contributors and team leaders with the ability to **track, analyze, and compare productivity** against benchmarks at a granular day-level.

---

## ✅ Features

- 🎯 **EmpID Slicer**  
  Quickly filter the entire dashboard to see the performance of any employee.

- 📅 **Date, Month & Day Filtering**  
  Dynamic dropdowns using a custom calendar table allow filtering by exact dates or full months.

- 📈 **Achieved vs Expected Tasks**  
  A powerful horizontal bar chart to compare actual output vs target workload.

- 📊 **Trend Chart**  
  Daily trend line showing task volume over time to identify patterns and outliers.

- 🧠 **KPI Cards**  
  - **Efficiency (%)** = (Achieved Tasks / Expected Tasks) × 100  
  - **Average Quality (%)** = From performance log  
  - **Time Utilization (%)** = Active tool time vs total  
  - **Availability Status** = Shows “Working”, “Leave Type” (e.g., SL, CL, OH, AL)

- 📋 **Detailed Table View**  
  See task breakdown per day, with totals automatically calculated.

---

## 📁 Dataset

- `DailyMetrics.csv`: Includes EmpID, Date, ExpectedTasks, AchievedTasks
- `QualityAndTU.csv`: Includes EmpID, Date, Quality Score, Time Utilization %
- `LeaveData.csv`: Includes EmpID, Date, LeaveType (SL, CL, OH, AL)
- Calendar Table generated using DAX

All data is simulated to mimic a real-world scenario in an operations/quality-based team environment.

---

## 🛠 Tools & Skills Used

- **Power BI Desktop**
- **Power Query Editor**
- **DAX Measures & Custom Columns**
- **Excel for structured inputs**
- **Row-Level Filtering Logic**
- **Calendar Table & Hierarchy**

---

## 📌 Business Use Case

This dashboard simulates a real-time performance tracker for use by:
- BPO/Operations/Tech Support managers to review employee metrics
- Employees themselves to reflect on daily trends
- HR teams to identify absenteeism, leave types, and quality gaps

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/628901cf-d7f3-45a7-b67e-50dc8a10bc47)

---

## 🚀 How to Use

1. Clone or download this repository
2. Open the `.pbix` file in Power BI Desktop
3. Load the data files (or replace with your own)
4. Interact with slicers and visuals to explore insights

---

## 🧠 Future Improvements

- Integrate Power BI Row-Level Security (RLS) for user-specific views
- Enable dynamic leave detection based on login hours
- Add export to PDF and auto-refresh options for publishing

---

## ✨ Author

**Mohamed Bin Badhusha E B**  
M.Tech Data Engineering | Aspiring Data Engineer  

___

