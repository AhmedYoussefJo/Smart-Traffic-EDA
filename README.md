# Smart Traffic Management - Data Analysis 🚦

## Overview
This project explores a **Smart Traffic Management Dataset** to extract valuable insights about traffic patterns, accidents, weather conditions, and vehicle behavior.  
The analysis is done using **Python (Pandas & Matplotlib)** with multiple visualizations to understand the data better.

---

## Steps Performed
1. **Data Cleaning:**
   - Converted `timestamp` to datetime.
   - Removed NaT values and missing entries.
   - Added `day` and `hour` columns for time-based analysis.

2. **Exploratory Data Analysis (EDA):**
   - **Accidents by Day** – Bar charts with highlighted max/min.
   - **Accidents by Location** – Comparison of accident density across locations.
   - **Weather Condition Analysis** – Pivot tables and bar charts.
   - **Traffic Volume vs Accidents** – Grouping data into ranges.
   - **Temperature Ranges** – Highlighting the most/least frequent ranges.
   - **Weather Distribution** – Pie chart of weather conditions.
---

## Visualizations
The analysis includes:
- **Bar Charts** (Accidents by Day, Location, Weather)
- **Pie Chart** (Weather Distribution)
- **Line Chart** (Accidents per Hour)
- **Custom Highlighted Ranges** (Temperature bins)

---

## Requirements
Install the required libraries:
```bash
pip install pandas matplotlib seaborn
