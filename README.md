# Data-Analyst-Internship-Task-5
Exploratory Data Analysis (EDA) on the Titanic dataset, focusing on survival factors and key trends.
#  Titanic Dataset Exploratory Data Analysis (EDA)

## Project Overview

This project is an **Exploratory Data Analysis (EDA)** of the classic Titanic survival dataset, fulfilling a data analysis internship task. The goal was to uncover key survival patterns, trends, and anomalies using Python's statistical and visualization libraries.

The full analysis workflow is documented in the Jupyter Notebook, and the formal conclusions are in the PDF report.

## 🛠️ Tools Used

* **Pandas:** Data loading, manipulation, and statistical summarization (`.info()`, `.describe()`, `.value_counts()`).
* **Seaborn & Matplotlib:** Data visualization (`sns.pairplot()`, `sns.heatmap()`, histograms, and bar plots).
* **Jupyter Notebook:** Interactive environment for documentation and code execution.

## 📊 Key Findings

The EDA established that survival was highly dependent on a few key features:

1.  **Gender (Dominant Factor):** **Females** had a dramatically higher survival rate ($\approx 74\%$) compared to males ($\approx 19\%$).
2.  **Socioeconomic Status:** **1st Class** passengers had the highest survival rate ($\approx 63\%$), confirming a strong correlation between Pclass and survival probability.
3.  **Data Quality:** Significant missing values were noted in the **`Cabin`** and **`Age`** columns, requiring imputation or special handling for future modeling.

---

## 📂 Repository Contents

* `Task5.jpynb`: The complete Python code and step-by-step analysis.
* `train.csv`: The source dataset used for the analysis.
* `Task 5_ Exploratory Data Analysis (EDA) Report on the Titanic Dataset.pdf`: The formal summary of findings and visual observations.
