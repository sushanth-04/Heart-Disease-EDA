# ❤️ Heart Disease EDA — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> Exploratory Data Analysis on a clinical heart disease dataset — uncovering risk factor patterns using Python, Pandas, Matplotlib & Seaborn.

---

## 📌 Project Overview

This project performs a comprehensive Exploratory Data Analysis (EDA) on a real-world heart disease dataset. The goal is to identify patterns, trends, and relationships between clinical features and the presence of heart disease — turning raw medical data into meaningful insights.

Built as part of my **Data Science Certification at [Innomatics Research Labs](https://www.innomatics.in/)**.

---

## 🎯 Objectives

- Understand the structure and distribution of clinical features
- Identify key risk factors associated with heart disease
- Handle missing values, outliers, and data quality issues
- Visualize relationships between features and target variable
- Draw data-driven conclusions that could support medical insight

---

## 📂 Dataset Information

| Attribute | Details |
|---|---|
| Source | UCI Heart Disease Dataset (Cleveland) |
| Records | 303 patient records |
| Features | 14 clinical attributes |
| Target | Presence of heart disease (0 / 1) |

**Key Features:**
- `age` — Age of the patient
- `sex` — Gender (1 = Male, 0 = Female)
- `cp` — Chest pain type (4 categories)
- `trestbps` — Resting blood pressure (mm Hg)
- `chol` — Serum cholesterol (mg/dl)
- `thalach` — Maximum heart rate achieved
- `exang` — Exercise-induced angina
- `target` — Heart disease present (1) or not (0)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python 3.x | Core programming language |
| Pandas | Data loading, cleaning & manipulation |
| Matplotlib | Custom visualizations |
| Seaborn | Statistical plots & heatmaps |
| Jupyter Notebook | Interactive analysis environment |

---

## 🔍 Analysis Workflow

```
1. Data Loading & Initial Inspection
        ↓
2. Data Cleaning (Missing Values, Duplicates, Data Types)
        ↓
3. Univariate Analysis (Distribution of each feature)
        ↓
4. Bivariate Analysis (Feature vs Target relationships)
        ↓
5. Correlation Analysis (Heatmap)
        ↓
6. Outlier Detection & Treatment
        ↓
7. Key Findings & Conclusions
```

---

## 📊 Key Findings

- **Age** is a significant factor — patients aged 50–65 show higher disease prevalence
- **Chest pain type (cp)** has a strong correlation with the target variable
- **Maximum heart rate (thalach)** is inversely related to heart disease presence
- **Males** in the dataset show higher disease rates than females
- **Cholesterol** alone is not a reliable standalone predictor

---

## 📁 Repository Structure

```
heart-disease-eda/
│
├── data/
│   └── heart.csv                  # Dataset
│
├── notebooks/
│   └── heart_disease_eda.ipynb    # Main EDA notebook
│
│
├── presentation/
│   └── HeartDiseaseProject.pptx    # Presentation slides
│
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/bvssushanth/heart-disease-eda.git
cd heart-disease-eda

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch Jupyter Notebook
jupyter notebook notebook/heart_disease_eda.ipynb
```

---

## 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
jupyter
```

> Install all with: `pip install -r requirements.txt`

---

## 🙏 Acknowledgements

This project was completed as part of my **Data Science Certification Program** at **[Innomatics Research Labs](https://www.innomatics.in/)**, Hyderabad. I'm grateful to the mentors and faculty for their guidance and for providing a hands-on, project-first learning environment.

---

## 🙋 About Me

**Venkata Sai Sushanth Bongarala**
Gradurated in B.Tech — Computer Science (AI & ML)
📍 Hyderabad, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/bvssushanth)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/sushanth-04)