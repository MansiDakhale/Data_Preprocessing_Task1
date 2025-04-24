# Data_Preprocessing_Task1

#  Titanic Survival Prediction - Preprocessing Pipeline

This project focuses on the data preprocessing steps for the Titanic dataset — a classic machine learning problem that predicts passenger survival based on various features.

---

##  Steps Completed

### 1. Data Loading
- Loaded Titanic dataset using `pandas`.

### 2. Data Exploration
- Inspected data types and null values.
- Identified categorical and numerical columns.

### 3. Missing Value Handling
- Imputed missing values:
  - `Age`: Filled using **median**.
  - `Fare`: Filled using **mean**.
  - `Embarked` and `Cabin`: Filled using **mode**.

### 4.Feature Encoding
- Converted categorical features to numerical:
  - `Sex`: Label encoded (Male = 0, Female = 1).
  - `Embarked` & `Cabin` Decks: One-hot encoded (e.g., `Embarked_Q`, `Deck_C`, etc.).

### 5.Feature Scaling
- Standardized numerical columns:
  - `Age`, `Fare`, `SibSp`, `Parch` scaled using **Z-score** normalization.

### 6. Outlier Removal
- Removed outliers using Z-score filtering (`|z| > 3`) from scaled numerical features.

---

## Output
- Cleaned and standardized dataset with encoded categorical variables.
- Ready for model training!

---

## Next Step
Proceed with **model training**, evaluation, and comparison (e.g., Logistic Regression, Random Forest, XGBoost).

---

##  Dataset Source

- [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

##  Author

- **Mansi Dakhale** – [MansiDakhale](https://github.com/MansiDakhale)

