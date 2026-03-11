# Ames Housing Data Statistical Analysis
---

## Technologies Used

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?style=flat-square&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=flat-square&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-orange?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4c72b0?style=flat-square)

## Overview
This repository contains a **comprehensive statistical analysis** of the **Ames Housing dataset (Iowa, USA)**. The project simulates the role of a **data analyst for a real estate firm**, aiming to identify key property characteristics using **descriptive statistics** to support strategic decision-making.

The study explores critical variables such as **sale price, living area, and material quality** to better understand market trends and detect potential anomalies in the dataset.

---

## Objectives & Requirements

- **Central Tendency Analysis**  
  Calculate **mean, median, and mode** to understand the baseline behavior of quantitative variables.

- **Distribution & Symmetry Evaluation**  
  Analyze the shape of data distributions using **histograms** and **mean vs. median comparisons**.

- **Dispersion & Variability Measurement**  
  Calculate **range, variance, standard deviation, and coefficient of variation (CV)** to evaluate dataset homogeneity.

- **Outlier Detection**  
  Identify anomalous records using the **Interquartile Range (IQR)** and **Z-Score methods**.

- **Correlation Analysis**  
  Compute **Pearson’s Correlation Coefficient** to determine relationships between structural features and the final **sale price**.

---

## Key Features

### Statistical Exploration
Use of **percentiles** to identify the **top 10% most expensive properties** in the dataset.

### Anomaly Detection Pipeline
Implementation of a workflow that **isolates outliers** and exports them into a **separate dataset** for further risk assessment.

### Influence Analysis
Correlation calculations to identify which features (**Living Area, Basement Size, or Overall Quality**) have the greatest impact on **property valuation**.

### Automated Data Export
Generation of a **CSV file containing only outlier properties**, enabling focused strategic review.


