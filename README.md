# 🌍 World Happiness Data Analysis

## 📌 Project Overview

This project analyzes the **World Happiness Report dataset** to identify the key factors that influence happiness across different countries and regions.

The goal is to explore whether **economic, social, and health-related factors** contribute to a better quality of life.

---

## 🎯 Objectives

* Check and correct data types in the dataset
* Handle missing values through data cleaning
* Perform exploratory data analysis (EDA)
* Identify relationships between key variables
* Build meaningful visualizations
* Create a dashboard to present insights

---

## 📊 Dataset Features

The dataset includes the following key variables:

* **Country** – Name of the country
* **Region** – Geographic region
* **Happiness Score** – Overall happiness level
* **Economy (GDP per Capita)** – Economic strength
* **Family** – Social support
* **Health (Life Expectancy)** – Average lifespan
* **Freedom** – Freedom to make life choices
* **Trust (Government Corruption)** – Perception of corruption
* **Generosity** – Level of generosity

---

## 🧹 Data Cleaning

* Converted incorrect data types into numeric format
* Identified and handled missing values using mean imputation
* Ensured dataset consistency for analysis

---

## 🔍 Exploratory Data Analysis (EDA)

### 1. Top 10 Happiest Countries

* Compared **GDP per Capita** and **Life Expectancy**
* Found that top countries generally have strong economies and healthcare systems

### 2. Correlation Analysis

* Measured relationships between variables
* Key findings:

  * GDP has a strong positive correlation with happiness
  * Health and family support are major contributors
  * Freedom also plays a significant role

### 3. GDP vs Happiness (Scatter Plot)

* Visualized how income affects happiness
* Observed that higher GDP often leads to higher happiness scores

### 4. Happiness by Region (Pie Chart)

* Compared average happiness across regions
* Highlighted regional disparities

### 5. Global Map Visualization

* Created an interactive map showing:

  * GDP per Capita (color scale)
  * Life Expectancy (hover information)

---

## 📊 Dashboard

A dashboard was created including:

* Bar chart (Top 10 countries)
* Scatter plot (GDP vs Happiness)
* Pie chart (Happiness by region)
* Map visualization (Global GDP distribution)

---

## 🧠 Key Insights

* Countries with higher GDP tend to have higher happiness levels
* Health (life expectancy) is one of the strongest predictors of happiness
* Social support (family) significantly impacts well-being
* Regional differences highlight inequality in global happiness

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Plotly

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/world-happiness-analysis.git
   ```

2. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn plotly
   ```

3. Run the Jupyter Notebook or Python script

---

## 📁 Project Structure

```
├── data/
│   └── 2016.csv
├── notebooks/
│   └── analysis.ipynb
├── visuals/
│   └── charts/
├── README.md
```

---

## 📌 Conclusion

This project demonstrates how data analysis can uncover meaningful insights into global well-being. Economic strength, health, and social support emerge as the most critical factors influencing happiness.

---

## 🙌 Author

**Tahmina Sahar**

Aspiring Data Analyst | Future Quantitative Analyst
Passionate about using data to solve real-world problems
