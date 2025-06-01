# Logistic Regression

This project demonstrates the use of **Logistic Regression** to predict passenger survival on the Titanic dataset. It covers complete data preprocessing, feature engineering, model training, evaluation, and visualization.

---

## Dataset
- **Source:** Titanic Dataset (Kaggle)
- **Objective:** Predict if a passenger survived (`Survived` column)

---
## Steps 

### 1. Data Cleaning & Preprocessing
- Visualized missing values and data quality
- Dropped columns with many missing values (`Cabin`)
- Removed irrelevant features: `PassengerId`, `Name`, `Ticket`
- Imputed missing `Age` values using median grouped by `Pclass` and `Sex`
- Filled missing `Embarked` values with the column mode

### 2. Feature Engineering
- Encoded categorical variables:
  - `Sex` using label encoding
  - `Embarked` using one-hot encoding
- Detected and removed outliers using box plots

### 3. Model Building
- Trained a Logistic Regression model
- Split data into training and testing sets for evaluation

### 4. Evaluation & Visualization
- Evaluated model performance with:
  - Accuracy score
  - Precision, Recall, F1-score (classification report)
  - ROC Curve visualization
  - AUC (Area Under Curve) score

---

## Results
- Logistic Regression achieved an accuracy of approximately **81.5%**
 
---
