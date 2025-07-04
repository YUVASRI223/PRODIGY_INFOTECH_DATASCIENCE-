
# PRODIGY\_INFOTECH\_DATASCIENCE: Task-05

 **Objective:**
The goal of this task is to analyze traffic accident data to uncover patterns related to **road conditions**, **weather**, and **time of day**. We aim to identify contributing factors, highlight accident hotspots, and visualize trends using data analytics and geospatial tools. This task enhances skills in EDA (Exploratory Data Analysis), feature engineering, and spatial data visualization.

 **Dataset Used:**

* **Source:** Open-source traffic accident dataset (assumed or provided)
* **Format:** CSV
* **Key Columns:** `timestamp`, `weather`, `road_condition`, `latitude`, `longitude`, `severity`

**Technologies Used:**

* Python 3.7+
* Pandas & NumPy for data manipulation
* Matplotlib and Seaborn for statistical visualization
* Folium for geospatial mapping
* Jupyter Notebook for development and presentation

 **Working:**

 **Data Loading and Inspection:**

* Loaded the dataset using Pandas and previewed structure with `.head()` and `.info()`.
* Checked for null values and data types to assess preprocessing needs.

 **Data Preprocessing:**

* Converted the `timestamp` column to Python datetime objects using `pd.to_datetime()`.
* Extracted `hour` and `day_of_week` for temporal analysis.
* Cleaned rows with missing critical fields (`weather`, `road_condition`, `latitude`, `longitude`).

 **Trend Analysis:**

 **By Road Condition:**

* Used `value_counts()` and bar plots to analyze accident frequency under different road conditions (e.g., Wet, Dry, Snowy).

 **By Weather Condition:**

* Grouped data by weather and plotted accident occurrences.

 **By Time of Day:**

* Visualized hourly accident frequency to identify peak hours (e.g., rush hours).
* Analyzed accidents by day of the week to detect weekday vs weekend trends.

🗺 **Geospatial Visualization (Hotspot Analysis):**

* Generated an interactive heatmap using Folium’s `HeatMap` plugin.
* Mapped latitude and longitude data to visualize high-risk locations.
* Saved as `accident_heatmap.html` for browser-based exploration.

 **Visualizations:**

* **Bar Charts:** Accidents by road/weather condition.
* **Line Graphs:** Hourly trends.
* **Heatmap (Seaborn):** Accident counts by combined weather and road conditions.
* **Geospatial Heatmap (Folium):** Accident density mapping.

 **Learning Outcomes:**

* Developed proficiency in handling time-based and geospatial data.
* Gained insights into accident-prone conditions and times.
* Learned to build heatmaps for location-based analysis.
* Strengthened Python data visualization skills using Matplotlib, Seaborn, and Folium.
* Understood the real-world significance of data in public safety and traffic planning.

 **Author:**
Yuva Sri
Data Science Student, VIT Vellore
Year: 2025

---

