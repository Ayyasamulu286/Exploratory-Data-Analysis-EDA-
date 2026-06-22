# Task 5 — Exploratory Data Analysis (EDA)
**Data Analyst Internship | DataX Labs**

## Objective
Perform EDA on the Mall Customers dataset to extract patterns, trends, correlations, and anomalies using statistical and visual techniques.

## Dataset
- **File:** `Mall_Customers.csv`
- **Rows:** 200 | **Columns:** 5
- **Features:** CustomerID, Gender, Age, Annual Income (k$), Spending Score (1-100)

## Tools & Libraries
Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

## Key Findings
- Most customers are aged 20–40 (right-skewed age distribution)
- **Age negatively correlates with spending score (r = -0.327)** — younger customers spend more
- Annual income does NOT predict spending (r = 0.010)
- 5 natural customer clusters visible in scatter plots
- Dataset is clean — 0 missing values

## Repository Structure
```
TASK-5-EDA/
├── Dataset/
│   └── Mall_Customers.csv
├── Notebook/
│   └── task5_eda.ipynb
├── Screenshots/
│   ├── histogram.png
│   ├── boxplot.png
│   ├── scatterplot.png
│   ├── heatmap.png
│   ├── pairplot.png
│   └── gender_pie.png
├── Report/
│   └── EDA_Report.pdf
├── README.md
└── requirements.txt
```

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook Notebook/task5_eda.ipynb
```
