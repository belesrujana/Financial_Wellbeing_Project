# Financial Well-Being Prediction Project

This project explores key metrics influencing financial well-being by applying classification and regression methods to data from the 2016 National Financial Well-being Survey.

Features

Data Handling**: Uploading and cleaning the dataset.
Classification Models**:
  - Random Forest Classifier
  - K-Nearest Neighbors (KNN) Classifier
  - AdaBoost Classifier
  - K-Fold Cross-Validation
  - Hyperparameter Tuning
  - 
Regression Models:
  - Multiple Linear Regression
  - Ordinary Least Squares (OLS) Regression
  - Multicollinearity and Variance Inflation Factor (VIF)
  - Recursive Feature Elimination (RFE)

Results

Best Performing Model**: Random Forest Classifier, with the highest cross-validation accuracy.
Significant Predictors**: Mortgage, savings, self-control, health, and material hardship.
Challenges**: The linear regression model showed a weak fit, indicating non-linear relationships between financial well-being and selected attributes.

Lessons Learned

Classification**: Behavioral factors significantly influence financial well-being, with classification models performing well.
Regression**: Improvements are needed in the regression model, possibly by reselection or transformation of variables to address non-linearity.

Files

- `NFWBS_PUF_2016_data.csv`: Survey data.
- `financial_wb.ipynb`: Project code.
- `Project Report - Copy.docx`: Final project report.
- `Financial Well-Being.pptx`: Summarized report.
---
