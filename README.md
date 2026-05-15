# ❤️ Heart Disease — Data Analysis Project

A beginner-friendly Exploratory Data Analysis (EDA) on a heart disease dataset using Python.

---

## 📁 Dataset
- **Source:** [Kaggle — Heart Disease Dataset](https://www.kaggle.com/datasets/nareshbhat/health-care-data-set-on-heart-attack-possibility)
- **File:** `heart.csv`
- **Size:** 303 patients, 14 columns

---

## 🛠️ Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 What's Covered
- Data cleaning (missing values, duplicates)
- Target variable distribution
- Age, gender, and chest pain analysis
- Cholesterol & blood pressure visualizations
- Correlation heatmap
- Outlier detection

---

## ▶️ How to Run

**Google Colab:**
```python
from google.colab import drive
drive.mount('/content/drive')

import pandas as pd
df = pd.read_csv('/content/drive/MyDrive/heart.csv')
```

**Jupyter Notebook:**
```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook Heart_Disease_EDA_Project.ipynb
```

---

## 🔍 Key Findings
- ~54% of patients in the dataset have heart disease
- Higher max heart rate is linked to heart disease
- Age group 45–65 is most affected
- `thalach`, `cp`, and `oldpeak` are most correlated with heart disease

---

*Made by AshwiniJindam*
