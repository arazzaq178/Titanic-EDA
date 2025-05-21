# Titanic-EDA # 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs an exploratory data analysis on the famous Titanic dataset to discover patterns related to passenger survival and behavior.

---

## 📁 Dataset
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- **File Used**: `Titanic-Dataset.csv`

---

## 📌 Objectives
- Load and inspect the dataset.
- Clean and preprocess the data.
- Visualize relationships between features.
- Detect outliers and missing values.
- Extract actionable insights.

---

## 🧰 Tools & Libraries
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 🔍 EDA Steps

### 1. Data Loading & Exploration
- Checked data shape, types, and basic stats.
- Used `info()`, `describe()`, `head()`.

### 2. Data Cleaning
- Handled missing values via median imputation.
- Removed irrelevant columns (e.g., `Cabin`).
- Dropped duplicate entries.
- Detected and removed outliers using IQR.

### 3. Visualization
- Bar plots for categorical variables (`Sex`, `Embarked`, `Pclass`)
- Histograms for numeric columns (`Age`, `Fare`)
- Correlation heatmap for numerical features

### 4. Insights Summary
- Female passengers had higher survival rates.
- 1st class passengers were more likely to survive.
- Young children (Age < 10) had higher survival rates.
- Fare and class were correlated with survival.

---

## 📊 Outputs
- Jupyter Notebook: `Titanic_EDA.ipynb`
- Python Script: `titanic_eda.py`
- Visualizations (saved as PNG)
- Presentation: `Titanic_EDA_Presentation.pptx`

---

## 🧠 Key Learnings
- Real-world data is messy.
- Visualization helps identify patterns quickly.
- Outlier detection is critical for accurate analysis.

---

## 📌 How to Run
1. Clone this repo
2. Install requirements: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook Titanic_EDA.ipynb`

---

## 📮 Contact
**Author**: Abdul Razzaq  
**Email**: [your-email@example.com]  
**GitHub**: [github.com/yourusername]

---
