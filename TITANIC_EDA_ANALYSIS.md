

# **PRODIGY\_INFOTECH\_DATASCIENCE: Task-02**

##  **Objective:**

The aim of this task is to perform **data cleaning** and **exploratory data analysis (EDA)** on a real-world dataset. We chose the **Titanic dataset** from [Kaggle](https://www.kaggle.com/c/titanic/data) to analyze survival patterns and understand relationships between variables such as **age, gender, class**, and **embarkation point**.

This helps in developing skills in preprocessing, visual storytelling, and extracting actionable insights from structured data.

---

##  **Dataset Used:**

* **Source:** Kaggle
* **Dataset:** Titanic - Machine Learning from Disaster
* **Format:** CSV (train.csv)
* **Link:** [https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/c/titanic/data)
* **Note:** The file `train.csv` must be downloaded manually and placed in the working directory.

---

##  **Technologies Used:**

* **Python 3.11+**
* **Pandas** for data analysis
* **NumPy** for numerical operations
* **Seaborn** and **Matplotlib** for plotting
* **Jupyter Notebook** or compatible Python IDE

---

##  **Working:**

###  **Data Loading:**

* The dataset is loaded using `pandas.read_csv`.
* Initial data exploration is done using `.head()`, `.info()`, and `.describe()`.

###  **Data Cleaning:**

* Missing values in `Age` and `Embarked` are filled using **median** and **mode** respectively.
* The `Cabin` column is dropped due to a high percentage of missing values.
* Unnecessary columns like `Name`, `Ticket`, and `PassengerId` are removed for clarity.

###  **Exploratory Data Analysis (EDA):**

#### **Univariate Analysis:**

* Count plots for `Survived`, `Pclass`, and `Sex`
* Histogram of `Age` with KDE (Kernel Density Estimate)

#### **Bivariate Analysis:**

* Survival rate by Gender (`Sex`)
* Survival rate by Passenger Class (`Pclass`)
* Heatmap showing correlation between numerical features

---

##  **Visualizations:**

###  Survival by Gender:

* Bar chart comparing male vs female survival rates
* X-axis: Gender | Y-axis: Count of passengers

###  Survival by Class:

* Stacked bar chart of survival across Pclass (1, 2, 3)
* Annotations added for clarity

###  Age Distribution:

* Histogram showing distribution of passenger ages
* KDE overlay highlights density
* Uses `seaborn.histplot` with 30 bins

###  Correlation Heatmap:

* Heatmap of correlation matrix between numerical columns
* Shows strongest survival indicators like `Sex` and `Pclass`

---

##  **Learning Outcomes:**

* Learned how to clean and preprocess a real-world dataset
* Identified missing data and used appropriate imputation strategies
* Gained hands-on experience with exploratory data analysis
* Visualized patterns in survival based on multiple factors
* Practiced creating professional-level plots and annotated visuals
* Understood how class, gender, and age affected survival on the Titanic

---

##  **Author:**

**Yuva Sri**
*Data Science Student, VIT Vellore*
**Year:** 2025

---




