# Obesity Risk Prediction (Statistical Learning)

Statistical learning project analyzing demographic, health, and lifestyle factors associated with obesity status.

This study evaluates multiple classification models and identifies **Random Forest** as the best-performing method for predicting obesity status.

The final model achieved **98.3% testing accuracy** using a Random Forest with **200 trees and 7 predictors per split**.

---

## Methods

The modeling pipeline included:

- Missing value analysis and **multiple imputation using `mice`**
- Exploratory data analysis of numerical and categorical predictors
- Multicollinearity analysis using **Variance Inflation Factor (VIF)**
- Cross-validated comparison of multiple statistical learning models
- Hyperparameter tuning and variable importance analysis for Random Forest

Models evaluated:

- **Probabilistic models:** Naive Bayes, K-Nearest Neighbors  
- **Linear models:** Logistic Regression, Ridge, Lasso, LDA, QDA  
- **Non-linear models:** Splines (GAM), Decision Trees, Bagging, Random Forest

---

## Results

Key findings:

- Linear and probabilistic models achieved **~68–75% accuracy**
- Non-linear models significantly improved performance
- **Random Forest achieved the highest testing accuracy (98.3%)**

Important predictive variables included:

- Age
- Height
- Physical activity frequency
- Water consumption
- Caloric intake behavior
- Family history of overweight

---

## Files

paper.pdf — final project paper
slides.pdf — project presentation
