# PRODIGY_INFOTECH_DATASCIENCE-01

**Objective:**

The aim of this task is to visualize population data using:

* A bar chart of the **Top 10 most populous countries**.
* A histogram showing the **distribution of population across all countries**.

This helps in understanding global demographic patterns, identifying skewness in population distribution, and gaining insights from visual exploration.

---

**Dataset Used:**

* **Source:** World Bank Open Data
* **Indicator:** SP.POP.TOTL (Total Population by Country)
* **Format:** CSV
* **Link:** [https://data.worldbank.org/indicator/SP.POP.TOTL](https://data.worldbank.org/indicator/SP.POP.TOTL)

> Note: The CSV file should be downloaded manually and placed in the working directory for analysis.

---

**Technologies Used:**

* Python 3.11+
* Pandas for data loading and manipulation
* Seaborn and Matplotlib for plotting
* Jupyter Notebook (or any Python IDE)

---

**Working:**

1. **Data Loading:**

   * The dataset is read from the CSV provided by the World Bank.
   * The most recent year (2022) is selected for analysis.

2. **Data Cleaning:**

   * Null values are handled (if any).
   * Columns are renamed for clarity.

3. **Bar Chart Creation:**

   * Top 10 countries by population are sorted and visualized.
   * Each bar is labeled with the population in millions.
   * A legend and rotation for labels improve readability.

4. **Histogram Creation:**

   * Histogram bins population data across all countries.
   * Each bar is labeled with the count of countries in that population range.
   * Legends and labeled axes make the chart informative.

---

**Visualizations:**

1. **Top 10 Bar Chart:**

   * X-axis: Country
   * Y-axis: Population (2022)
   * Added data labels on each bar
   * Viridis color palette
   * Includes a legend

2. **Population Histogram:**

   * Shows how countries are distributed by population size
   * Annotated with frequencies
   * Uses skyblue bars with black edges

---

**Learning Outcomes:**

* Understood how to use real-world open data from global sources (World Bank).
* Learned to preprocess and visualize large-scale population data.
* Applied `Seaborn` and `Matplotlib` for customized plots.
* Practiced adding annotations, legends, and layout adjustments.
* Gained insights into population skewness and outliers.

---

**Author:**
Yuva Sri
Data Science Student, VIT Vellore
Year: 2025

---

