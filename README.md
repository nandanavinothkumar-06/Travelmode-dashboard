#  Travel Mode Analysis Dashboard | Tableau Project

##  Project Overview

The **Travel Mode Analysis Dashboard** is an interactive Tableau dashboard designed to analyze and compare different transportation modes based on key travel metrics such as:

- Travel Cost
- Travel Distance
- Waiting Time
- Efficiency Score
- Traveler Distribution

This project focuses on transforming raw travel-related data into meaningful business insights through effective data visualization and dashboard storytelling.

The dashboard enables users to quickly identify the most efficient travel mode, understand travel behavior patterns, and compare transportation options visually.

---

#  Objectives

The main objectives of this project were to:

- Analyze transportation modes using visual analytics
- Compare travel cost and waiting time across modes
- Identify the most efficient travel option
- Create an interactive and professional Tableau dashboard
- Practice KPI creation and dashboard design principles

---

#  Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Tableau | Dashboard Development & Visualization |
| Calculated Fields | KPI & Efficiency Score Calculation |
| Interactive Filters | User-driven Analysis |
| Data Visualization Techniques | Comparative Analytics |

---

#  Dataset Information

The dataset contains transportation-related information including:

| Column Name | Description |
|---|---|
| Mode | Type of transportation |
| Travel | Travel distance |
| Gcost | Travel cost |
| Wait | Waiting time |
| Income | Traveler income |
| Size | Group size |
| Vcost | Vehicle cost |
| Choice | User travel preference |

---

#  Dashboard Components

##  KPI Cards

The dashboard includes key performance indicators for quick analysis:

- **Average Travel Cost**
- **Total Travelers**
- **Average Wait Time**
- **Most Efficient Travel Mode**

---

##  Visualizations Included

### 1️) Travel Distance vs Cost Analysis
- Bubble chart comparing travel distance and cost across transportation modes
- Bubble size represents overall travel magnitude

### 2️) Average Travel Cost by Mode
- Horizontal bar chart comparing average travel cost

### 3️) Average Wait Time by Mode
- Comparative visualization of waiting times

### 4️) Travel Efficiency Score by Mode
- Custom efficiency metric used to determine the best travel option

### 5️) Wait Time Distribution
- Histogram showing how waiting times are distributed

---

#  Calculated Field Used

## Efficiency Score

```text
SUM([Travel]) / SUM([Gcost] + [Wait])
```

This metric helps evaluate transportation modes based on:
- Higher travel coverage
- Lower travel cost
- Lower waiting time

---

#  Key Insights Generated

-  **Car** is the most efficient travel mode overall
-  **Air travel** has the highest average waiting time
-  **Train travel** shows the highest average travel cost
-  **Bus and Train** modes cover the longest travel distances
- Most waiting times are concentrated below **70 minutes**

---

#  Dashboard Features

✅ Interactive Mode Filter  
✅ Dynamic Tooltips  
✅ KPI Cards  
✅ Clean Layout Design  
✅ Comparative Visual Analysis  
✅ Business Insight Section  
✅ User-Friendly Dashboard Interface

---

#  Dashboard Preview

## Main Dashboard
<img width="1366" height="768" alt="Travel mode analysis" src="https://github.com/user-attachments/assets/d8bae22d-5b98-4753-b7bd-d087f830d164" />


---

#  How to Run the Project

1. Download the Tableau workbook file (`.twbx`)
2. Open using Tableau Public/Desktop
3. Explore the dashboard interactively
4. Use filters to analyze specific travel modes

---

#  Skills Demonstrated

This project demonstrates practical understanding of:

- Tableau Dashboard Development
- Data Storytelling
- Business Intelligence Concepts
- KPI Design
- Data Visualization Best Practices
- Analytical Thinking
- Interactive Dashboard Building

---

#  Future Improvements

Possible future enhancements include:

- Adding geographical travel mapping
- Time-series travel trend analysis
- Predictive travel cost forecasting
- Advanced dashboard interactivity
- Integration with real-time transportation datasets

---

#  Author

## Nandana Vinothkumar
