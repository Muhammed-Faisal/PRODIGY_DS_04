# PRODIGY_DS_03 - Bank Marketing Prediction

This project is part of my Data Science Internship at **Prodigy InfoTech**.

## Task Description

**Task 03:** Build a Decision Tree Classifier to predict whether a customer will purchase a product or service based on demographic and behavioral data.

## Dataset

- Source: [Bank Marketing Dataset - UCI Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- Format: CSV with semicolon-separated values

## Key Steps

1. **Data Preprocessing:**
   - Handled categorical variables using `OneHotEncoder` and `OrdinalEncoder`
   - Applied feature scaling where needed
   - Separated target variable `y`

2. **Modeling:**
   - Built a `DecisionTreeClassifier` using a pipeline
   - Split data into train/test sets
   - Used cross-validation for performance assessment

3. **EDA:**
   - Visualized job, education, marital status distributions
   - Checked class imbalance in target variable
   - Analyzed feature importance using decision tree outputs

## Tools Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

## Outcome

Gained hands-on experience in model building and preprocessing for classification tasks. Decision Trees offered valuable insights into feature importance for targeted marketing.

---

**Internship**: Prodigy InfoTech  
**Task**: PRODIGY_DS_03 - Customer Conversion Classifier
