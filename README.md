# 🩺 Diabetes Readmission EDA Project

This project performs Exploratory Data Analysis (EDA) on a real-world healthcare dataset containing over 100,000 hospital admissions for diabetic patients. The goal is to uncover patterns that relate to early hospital readmissions (within 30 days), which are a key quality-of-care metric in healthcare.

## 📂 Dataset

- **File**: `diabetic_data.csv`
- **Source**: UCI Machine Learning Repository (130 US hospitals, 1999–2008)

## 🎯 Project Objectives

- Explore trends across patient demographics (age, race, gender)
- Analyze relationships between diabetes medication use and readmission status
- Understand how hospital length of stay impacts readmission risk
- Identify high-risk groups based on race, gender, and age
- Provide actionable insights for predictive modeling

## 🛠️ Tools & Libraries Used

- Python 3
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

## 🧪 How to Run This Project

1. Download this repository or clone it via Git.
2. Make sure `diabetic_data.csv` is in the same folder as `EDA_Diabetes.ipynb`.
3. Launch Jupyter Notebook or open the notebook via VS Code.
4. Run the notebook step by step to follow the analysis.

## 📈 Key Insights

- Most early readmissions occurred in patients aged 70–80.
- Patients who were prescribed diabetes medication showed higher readmission rates, possibly due to higher severity.
- Caucasian, Female patients aged 70–80 were among the most frequently readmitted groups.
- Shorter hospital stays didn't always prevent readmission — in some cases, they correlated with early return.

## ✅ Project Status

- ✔️ EDA complete
- 🔍 High-risk group profiling included
- 🚀 Ready for feature engineering and machine learning

## 📌 Notes

- The notebook is fully portable if the CSV file is placed in the same directory.
- All visualizations include proper labels and titles for easy interpretation.

