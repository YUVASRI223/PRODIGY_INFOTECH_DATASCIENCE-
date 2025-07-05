Here's a much shorter README for Task 5:

---

## PRODIGY_INFOTECH_DATASCIENCE: Task-05

### Project Title
**Traffic Accident Data Analysis: Patterns & Contributing Factors**

### Objective
Analyze traffic accident data (`acc_20.csv`) to identify patterns related to time, weather, and road conditions. Visualize key contributing factors and identify regional accident hotspots.

### Dataset Used
* **File:** `acc_20.csv`
* **Content:** Traffic accident records.
* **Key Data Points:** Time (`HOUR`, `DAY_WEEKNAME`, `MONTHNAME`), Weather (`WEATHERNAME`, `LGT_CONDNAME`), Road/Environmental (`URBANICITYNAME`, `WRK_ZONE`, `INT_HWYNAME`, `ALCOHOLNAME`), Location (`REGIONNAME`), Severity (`MAX_SEV`, `MAX_SEVNAME`), Injuries (`NUM_INJ`).
* **Note:** Lacks precise latitude/longitude or `CITY` data, so hotspot analysis is regional.

### Technologies Used
* Python 3.x
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

### Working Highlights
* **Data Prep:** Loaded `acc_20.csv`, converted relevant columns to numeric, and handled missing values.
* **Temporal Analysis:** Visualized accident counts by hour, day of week, month, and year.
* **Environmental Factors:** Explored impacts of weather, light conditions, urbanicity, work zones, interstate highways, and alcohol on accidents.
* **Regional Hotspots:** Identified regions with highest accident frequencies due to lack of granular geographical data.
* **Severity & Injuries:** Analyzed accident severity and average injuries across different times and weather conditions.

### Learning Outcomes
* Practical experience in traffic accident data analysis.
* Proficiency in data cleaning, type conversion, and feature utilization.
* Skills in generating insightful visualizations for temporal, environmental, and regional patterns.
* Ability to adapt analysis based on data limitations (e.g., no geo-coordinates).

### Author
Yuva Sri
Data Science Student, VIT Vellore
Year: 2025

---
