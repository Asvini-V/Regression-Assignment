# Regression Assignment – Insurance Charges Prediction

## Problem Statement
The objective of this project is to predict insurance charges based on customer details such as age, sex, BMI, number of children, and smoking status using supervised machine learning regression techniques.

## Dataset
- File: `insurance_pre.csv`
- Total records: 1339
- Features:
  - Age
  - Sex
  - BMI
  - Children
  - Smoker
- Target variable:
  - Charges

## Data Preprocessing
- Categorical features (`sex`, `smoker`) were nominal in nature.
- One-Hot Encoding was applied to convert categorical variables into numerical format.
- The dataset was split into training and testing sets.

## Model Development
Multiple regression models were developed and implemented, including:
- Multiple Linear Regression
- Support Vector Machine Regression
- Decision Tree Regression
- Random Forest Regression

## Model Evaluation
- Model performance was evaluated using the R² score.
- Different parameter combinations were tested for SVM, Decision Tree, and Random Forest models.
- The R² scores of all models were documented and compared.

## Final Model Selection
Random Forest Regression was selected as the final model as it achieved the highest R² score (0.87) and showed stable performance across different parameter combinations.

## Project Files
- `Phase1.ipynb` – Data preprocessing, model training, and evaluation
- `Phase2-Deployment.ipynb` – Model saving, loading, and prediction
- `finalized_model_RF.sav` – Saved Random Forest model
- `insurance_pre.csv` – Dataset used 
- `Document.docx.pdf` – Detailed project report
- `README.md` – Project overview

## Conclusion
This project demonstrates that ensemble models like Random Forest provide better predictive performance for insurance charge prediction compared to individual regression models.


