# Elevate_Lab_Tasks_2
INTERN AT ELEVATE LABS TASKS
# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project is part of the **AI & ML Internship** Task 2, where we perform EDA using the Titanic dataset. The goal is to understand the dataset using descriptive statistics and visualizations.

---

## 📌 Objective

To understand the dataset using statistical summaries and visualizations. We aim to explore patterns, relationships, and potential insights that might affect survival rates.

---

## 🛠 Tools Used

- Python
- Pandas
- Seaborn
- Matplotlib
- Plotly Express

---

## 📂 Dataset

We used the popular Titanic dataset from Kaggle. It contains information about passengers such as age, sex, ticket class, and survival status.

### Key Columns:
- `PassengerId`
- `Survived` (Target variable)
- `Pclass` (Passenger class)
- `Name`
- `Sex`
- `Age`
- `SibSp` (Number of siblings/spouses aboard)
- `Parch` (Number of parents/children aboard)
- `Fare`
- `Cabin`
- `Embarked`

---

## 📊 EDA Tasks Performed

1. **Handling Missing Values**: Dropped rows with missing values in `Age` and `Sex` for clean visualizations.
2. **Age Distribution by Gender**:
   - Used **Plotly** to create a histogram of age distribution colored by gender.
   - Added marginal boxplots for better distribution insight.

   ![age plot]

3. **Survival by Passenger Class**:
   - Used **Seaborn Countplot** to visualize survival counts across different classes (`Pclass`).

4. **Survival by Gender**:
   - Visualized how gender affects survival using Seaborn countplot grouped by `Survived`.

---

## 📌 What I Learned

- How to generate summary statistics and clean data using pandas.
- How to create insightful visualizations using Seaborn and Plotly.
- How to compare categorical variables (like gender and class) with survival outcomes.
- Basics of pattern recognition and feature-level insights from visual data.

---

## ✅ Future Work

- Create a heatmap of correlation between features.
- Build classification models to predict survival.
- Engineer new features (e.g., Family size, Title extraction from Name).
