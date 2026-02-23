# 🩺 Heart Disease Data Analysis & Preprocessing

This project focuses on cleaning and exploring healthcare data to prepare it for machine learning. 

## 🛠️ Key Data Cleaning Steps
In this project, I performed the following "Quality Assurance" steps:
* **Null Detection:** Identified missing values across 13 clinical features.
* **Mean Imputation:** Filled missing numerical values with the mean to maintain a robust sample size.
* **Outlier Handling:** Addressed "0" values in cholesterol and blood pressure columns, treating them as data entry errors.

## 📊 Visualizing Correlations
After cleaning, I generated a **Correlation Heatmap** to identify which health factors (like age, cholesterol, and max heart rate) have the strongest relationship with heart disease.

## 🚀 Technologies Used
* **Python** (Pandas, Seaborn, Matplotlib)
* **Jupyter Notebook**
* **Git/GitHub** for version control

## 📝 How to Use
1. Clone this repo.
2. Run `pip install pandas seaborn matplotlib`.
3. Open `your_filename.ipynb` to see the full analysis.

![Heatmap](visuals/correlation_heatmap.png)
