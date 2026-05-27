# Titanic Data Science Project
### DecodeLabs Data Science Internship

---

## Project Overview

This project was completed as part of the **DecodeLabs Data Science Internship**.  
It covers all 5 tasks using the **Titanic dataset** — analyzing passenger survival data through the full data science pipeline: from data collection to predictive modeling.

---

## Tasks Completed

| # | Task | Description | Status |
|---|------|-------------|--------|
| 1 | Data Collection & Dataset Understanding | Loaded dataset, explored columns, data types, and structure | Done |
| 2 | Data Cleaning & Preprocessing | Handled missing values, removed duplicates, encoded categories | Done |
| 3 | Exploratory Data Analysis (EDA) | Statistics, survival rates, outlier detection, correlations | Done |
| 4 | Data Visualization | 7 charts: countplot, barplot, KDE, boxplot, heatmap | Done |
| 5 | Predictive Model | Logistic Regression classifier with ~80% accuracy | Done |

---

## Repository Structure

```
decodelabs-data-science/
│
├── decodelabs_data_science_internship.ipynb   <- Main notebook (all 5 tasks)
├── titanic_visualizations.png                 <- Exported visualization chart
└── README.md                                  <- Project documentation
```

---

## Dataset

- **Name:** Titanic Passenger Survival Dataset
- **Source:** Seaborn built-in datasets (originally from [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic))
- **Size:** 891 rows x 15 columns
- **Target variable:** `survived` (0 = did not survive, 1 = survived)
- **How to load:**
```python
import seaborn as sns
df = sns.load_dataset('titanic')
```

---

## Technologies Used

| Tool | Purpose |
|------|---------|
| Python 3 | Main programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Seaborn | Dataset loading & visualization |
| Matplotlib | Plotting charts |
| Scikit-learn | Machine learning model |
| Google Colab | Development environment |

---

## How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload `decodelabs_data_science_internship.ipynb`
3. Run all cells from top to bottom (`Runtime -> Run all`)
4. No additional installations needed — all libraries are pre-installed in Colab

---

## Key Findings

- Overall survival rate: **~38.4%**
- Females survived at **~74%** vs males at **~19%**
- 1st class passengers survived at **~63%** vs 3rd class at **~24%**
- Model accuracy: **~80%** using Logistic Regression
- Strongest predictors: **gender** and **passenger class**

---

## Notes

- All code written from scratch — no plagiarized or copied code
- Notebook is self-contained and runs fully on Google Colab
- Dataset loads automatically via `seaborn` (no file upload needed)

---

## Connect with DecodeLabs

- Website: [decodelabs.tech](https://www.decodelabs.tech)
- LinkedIn: [decodelabs](https://www.linkedin.com/company/decodelabs)
- Instagram: [@official_decodelabs](https://instagram.com/official_decodelabs)
- Telegram: [t.me/decodelabs_tech](https://t.me/decodelabs_tech)

---

*DecodeLabs Data Science Internship — 2025*
