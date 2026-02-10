# Newborn-Health-Monitoring-Analysis-using-Python
This analysis focuses on providing insights to the newborn health monitoring dataset
# 🩺 Newborn Health Monitoring Analysis

This repository contains a data science project focused on analyzing newborn health indicators to assess potential health risks, growth patterns, and the relationship between key medical parameters such as jaundice levels, oxygen saturation, and immunization status.  

The project leverages Python-based data analytics and visualization to uncover patterns useful for pediatric health monitoring and decision support.

---

## 📘 Project Overview

Early detection and monitoring of newborn health issues are critical for improving neonatal outcomes.  
This notebook explores relationships among clinical indicators such as:

- **Jaundice levels (mg/dL)**  
- **Oxygen saturation (%)**  
- **Birth weight and weight progression over time**  
- **Immunization completion and risk levels**

The analysis uses statistical correlations, visualizations, and time-series tracking to identify trends and potential early warning signs in newborn health data.

---

## 📂 Repository Structure
-Newborn Health Monitoring Analysis.ipynb # Main analysis notebook
-data/ Folder for raw or processed datasets
-outputs/ Visualizations or results
- README.md # Project documentation

---

## 🧮 Dataset Description

The dataset includes newborn health records with the following key columns (fields may vary):

| Column Name              | Description |
|---------------------------|-------------|
| `baby_id`                | Unique identifier for each newborn |
| `age_days`               | Age of the newborn in days |
| `weight_kg`              | Recorded weight of the baby |
| `jaundice_level_mg_dl`   | Bilirubin level indicating jaundice severity |
| `oxygen_saturation`      | Blood oxygen percentage |
| `immunizations_done`     | Whether immunizations were completed (Yes/No) |
| `risk_level`             | Classified health risk level (Low, Moderate, High) |

---

## 🔍 Analysis Summary

### 1. **Exploratory Data Analysis (EDA)**
- Examined distributions and outliers in health indicators.  
- Compared average measurements across risk categories.  

### 2. **Correlation Analysis**
- Investigated relationships between **jaundice levels** and **oxygen saturation**:
### 3. Immunization vs. Risk Level

Visualized the relationship between immunization completion and risk level:

### 4. Weight Tracking

Monitored growth trajectories for individual newborns:

📊 Key Insights

Newborns with higher jaundice levels tend to have lower oxygen saturation, indicating potential respiratory or liver function concerns.

Incomplete immunizations are often associated with higher health risk classifications.

Weight progression over the first days shows strong predictive value for early development status.

🚀 Results & Conclusions

The notebook provides:

Statistical evidence of correlation between jaundice severity and oxygen saturation.

Visual insight into the role of immunization and growth patterns.

Frameworks for developing predictive models for neonatal risk assessment.

These insights can support healthcare providers and researchers in designing improved newborn monitoring systems.


🧠 Technologies Used

Python
pandas, numpy

matplotlib, seaborn

Jupyter Notebook
