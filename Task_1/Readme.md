# CodeAlpha Data Analytics Internship - Task 1
# Exploratory Data Analysis (EDA) on Titanic Dataset

This folder contains the first task for the CodeAlpha Data Analytics Internship. The goal of this project is to perform an in-depth Exploratory Data Analysis (EDA) on the classic Titanic dataset to uncover factors that influenced passenger survival rates.

## 📌 Project Overview
This project explores the passenger manifest to understand demographics, ticket fares, cabin locations, and family sizes, and how these variables correlate with the survival rate.

## 📊 Key Insights & Features
* Data Cleaning: Handled missing values in critical columns like Age and Embarked. Dropped unnecessary columns for better statistical stability.
* Demographics Profiling: Explored how gender (Sex) and age influenced survival. Verified the historical "Women and children first" evacuation protocol.
* Socio-Economic Factors: Analyzed the survival metrics across different passenger classes (Pclass). Discovered a strong correlation between higher ticket fares and survival probability.
* Feature Correlation: Built a visual correlation heatmap to discover underlying statistical dependencies between numerical columns.

## 📈 Visual Analysis
The analysis includes a correlation matrix heatmap (correlation_heatmap_2.png) that visually demonstrates how different numerical features like Class, Fare, and Age align with survival outcomes.

## 🛠️ Tech Stack & Libraries Used
* Language: Python
* Environment: Jupyter Notebook
* Libraries: pandas, numpy, matplotlib, seaborn

## 🚀 How to Run Locally

1. Clone the repository:
   git clone https://github.com/AnujKumarTiwari/CodeAlpha_ProjectName.git
   cd CodeAlpha_ProjectName/Task_1

2. Install required dependencies:
   pip install numpy pandas matplotlib seaborn notebook

3. Launch the Jupyter Notebook:
   jupyter notebook titanic_eda_2.ipynb

---
💡 Developed by Anuj Kumar Tiwari as part of the CodeAlpha Data Analytics Internship.
