## 📁 Project Overview
This project performs an exploratory data analysis (EDA) on a sample Titanic dataset using Python (Pandas, Seaborn, Matplotlib). The goal is to uncover insights regarding passenger survival based on various features such as age, gender, class, and more.

---

## 📌 Objectives
- Load and clean the dataset
- Handle missing data
- Analyze survival rates by gender and class
- Visualize important distributions and relationships
- Generate actionable insights

---

## 🛠️ Tools Used
- Python 3.x
- Pandas
- Seaborn
- Matplotlib

---

## 📂 Files
- `dataset3 - Sheet1.csv` : The Titanic dataset file.
- `titanic_eda.py` : Python script for data analysis and visualization.
- `README.md` : Project documentation.

---

## 🔍 EDA Tasks Performed

### ✅ Data Cleaning
- Removed rows with missing `Age` and `Embarked`
- Filled missing `Cabin` entries with `'Unknown'`

### ✅ Grouping & Aggregation
- Survival rate by `Sex`
- Survival rate by `Pclass`
- Survival rate by both `Pclass` and `Sex`

### ✅ Visualizations
- **Histogram**: Age distribution
- **Barplot**: Survival rates by class and gender
- **Heatmap**: Correlation between numeric features

---

## 📈 Key Insights

- **Gender**: Male passengers had a higher survival rate than females in this sample.
- **Class**: 1st class passengers had the highest survival rate.
- **Age**: Most passengers were between 20-40 years old.
- **Fare**: Positively correlated with survival; passengers who paid higher fares had better survival chances.
- **Pclass**: Negatively correlated with survival; higher class (lower number) linked with more survival.

---

## 🚀 How to Run
1. Ensure `dataset3 - Sheet1.csv` is in your working directory.
2. Run the Python script:

```bash
python titanic_eda.py
