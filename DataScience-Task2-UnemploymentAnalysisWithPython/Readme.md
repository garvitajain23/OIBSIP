# 📊 Unemployment Analysis with Python

## 🎯 Task 2 — Unemployment Analysis with Python

### 📌 Objective

The objective of this project is to perform **Exploratory Data Analysis (EDA)** on unemployment data from India to identify **regional and temporal trends** in unemployment rates, with special emphasis on the impact of the **COVID-19 pandemic**.

The analysis examines how unemployment varied across different states and regions over time and compares unemployment rates before and after the onset of the COVID-19 pandemic.

---

## 🛠️ Tech Stack

* 🐍 Python
* 🐼 Pandas
* 📈 Matplotlib
* 🎨 Seaborn
* 📓 Jupyter Notebook / Google Colab

---

## 📂 Dataset

The dataset used in this project is **"Unemployment in India"**, publicly available on Kaggle.

The dataset contains information such as:

* 🗺️ Region / State
* 📅 Date
* 📉 Estimated Unemployment Rate (%)
* 👥 Estimated Employed
* 📊 Estimated Labour Participation Rate (%)
* 🏙️ Area (Urban/Rural)

The dataset is loaded into a Pandas DataFrame for analysis.

---

## 🧹 Data Preparation

The following preprocessing steps are performed:

* 📥 Load the dataset using Pandas.
* 🔍 Inspect the dataset shape.
* 🏷️ Check column names and data types.
* ❌ Check for missing (null) values.
* 📅 Convert the date column into datetime format.
* 🧽 Remove unnecessary whitespace from column names where required.

---

## 🔎 Exploratory Data Analysis (EDA)

The analysis includes:

* 📊 Dataset overview.
* 🗺️ Region-wise average unemployment rates.
* 📅 Month-wise unemployment trends.
* 🌎 Comparison of unemployment rates across different states.
* 📈 Analysis of unemployment changes over time.

---

## 📈 Data Visualisations

### 1️⃣ 🗺️ Region-wise Average Unemployment Rate

A bar chart is used to compare the **average unemployment rate across different states and regions of India**.

### 2️⃣ 📅 Month-wise Trends

Monthly unemployment trends are analysed to understand **temporal and seasonal changes** in unemployment rates.

### 3️⃣ 📈 Time-Series Analysis

A time-series line chart is created to show unemployment rates over time for **at least three major states or regions**.

This helps visualize changes in unemployment during the COVID-19 pandemic.

### 4️⃣ 🏆 Top 10 States with Highest Average Unemployment Rate

A bar chart displays the **top 10 states with the highest average unemployment rates** during the period covered by the dataset.

### 5️⃣ 🔥 Correlation Heatmap

A Seaborn heatmap is used to examine the relationships between:

* 📉 Estimated Unemployment Rate (%)
* 👥 Estimated Employed
* 📊 Estimated Labour Participation Rate (%)

The heatmap helps identify **positive and negative correlations** among these variables.

---

## 🦠 COVID-19 Impact Analysis

To study the effect of the COVID-19 pandemic, the dataset is divided into two periods:

* 🟢 **Pre-COVID Period**
* 🔴 **Post-COVID Period**

The mean unemployment rate is calculated for both periods and compared.

This comparison helps identify the changes in unemployment associated with the COVID-19 pandemic.

---

## 💡 Key Observations

The analysis focuses on observations such as:

* 🗺️ Some states consistently experienced higher unemployment rates than others.
* 📈 Unemployment rates showed noticeable fluctuations over time.
* 🦠 Several regions experienced a sharp increase in unemployment around the beginning of the COVID-19 pandemic.
* 📊 The comparison between pre-COVID and post-COVID periods highlights significant changes in unemployment levels.
* 🔗 Employment and labour participation rates show meaningful relationships with unemployment rates, as observed from the correlation heatmap.

Detailed observations are included as **Markdown cells between the visualisations** in the Jupyter Notebook.

---

## 📁 Project Structure

```text
Unemployment-Analysis/
│
├── 📓 Unemployment_Analysis.ipynb
├── 📊 Unemployment_in_India.csv
└── 📄 README.md
```

---

## 🚀 How to Run

1. 📥 Download the **Unemployment in India** dataset from Kaggle.
2. 📂 Place the CSV file in the project folder or upload it to Google Colab.
3. 📓 Open `Unemployment_Analysis.ipynb`.
4. ▶️ Run all notebook cells sequentially.
5. 📊 Review the EDA results, visualisations, and observations.

---

## ✅ Task Checklist

* [x] 📥 Download a suitable unemployment dataset.
* [x] 🐼 Load the dataset using Pandas.
* [x] 🔍 Inspect dataset shape.
* [x] ❌ Check for null values.
* [x] 📅 Convert the date column to datetime format.
* [x] 🗺️ Perform region-wise unemployment analysis.
* [x] 📆 Analyse month-wise unemployment trends.
* [x] 📈 Create time-series charts for major states.
* [x] 🏆 Create a bar chart for the top 10 states with the highest average unemployment rate.
* [x] 🔥 Create a correlation heatmap.
* [x] 🦠 Compare unemployment rates before and after COVID-19.
* [x] 💬 Add written observations between charts.
* [x] 🧹 Keep the notebook clean and well-commented.

---

## 🏁 Conclusion

This project demonstrates how **Python and data analysis techniques** can be used to study unemployment trends and identify important regional and temporal patterns.

By combining **Exploratory Data Analysis, data visualisation, time-series analysis, and correlation analysis**, the project highlights differences in unemployment across Indian states and examines the impact of the COVID-19 pandemic on unemployment rates.

---

## 👩‍💻 Author

**Garvita Jain**

*Data Science Internship — Task 2*
