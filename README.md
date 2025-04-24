# 🧹 Task 1: Data Cleaning & Preprocessing – Titanic Dataset

## 🎯 Objective
The main objective of this task is to clean and preprocess the Titanic dataset in preparation for machine learning models. This is a crucial step in any data science workflow, as clean and structured data leads to more accurate and reliable models.

---

## 🗃️ Dataset
- Source: [Kaggle – Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- The dataset contains details of passengers like age, fare, gender, etc., and whether they survived the Titanic shipwreck.

---

## 🧰 Tools & Libraries
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 🔧 Steps Performed

1. **Load the Dataset**  
   Read the CSV file into a DataFrame using Pandas.

2. **Explore the Dataset**  
   Understand structure, data types, and null values using `.info()`, `.describe()`, and `.isnull()`.

3. **Handle Missing Values**  
   - Fill numerical columns using median.
   - Fill categorical columns using mode.
   - Drop columns with excessive missing values (e.g., Cabin).

4. **Encode Categorical Variables**  
   - Applied Label Encoding for 'Sex' and 'Embarked'.

5. **Feature Scaling**  
   - Used StandardScaler to standardize 'Age' and 'Fare'.

6. **Outlier Detection & Removal**  
   - Visualized using boxplots.
   - Removed extreme outliers using Z-score method.

---

## 📈 Output
A cleaned, encoded, and scaled version of the Titanic dataset, ready for use in ML algorithms.

---

## 🧠 Interview Questions Covered
- Types of missing data
- Handling categorical variables
- Normalization vs Standardization
- Outlier detection methods
- Importance of preprocessing
- One-Hot vs Label Encoding
- Data imbalance handling
- Impact of preprocessing on accuracy

---

## 📁 Files Included
- `task1_cleaning.ipynb` – Jupyter notebook with step-by-step code
- `README.md` – This file explaining the task
- (Optional) Screenshots of visualizations

---

## 🔗 Submission
After pushing the repository to GitHub, submit the link using the provided Google Form.

---
