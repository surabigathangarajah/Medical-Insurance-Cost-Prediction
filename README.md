# Medical-Insurance-Cost-Prediction
Project Overview
Built a machine learning regression model to predict medical insurance costs based on age, BMI, smoking habits, number of children, sex, and region.

# Dataset
- Source: Kaggle Medical Cost dataset
- Features:
  - age, sex, bmi, children, smoker, region
- Target:
  - charges (insurance cost)

Steps
1. Data preprocessing (scaling numeric features, encoding categorical features)
2. Exploratory Data Analysis (distribution of charges, smoker vs charges, BMI vs charges)
3. Model Training:
   - Linear Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
4. Model Evaluation:
   - Metrics: MAE, RMSE, R²
   - Feature importance
5. Insights & Observations

Results

| Model                | MAE       | RMSE      | R² Score |
|---------------------|-----------|-----------|----------|
| Linear Regression    | 4181.19  | 5796.28  | 0.78     |
| Random Forest        | 2521.98  | 4548.38  | 0.87     |
| Gradient Boosting    | 2530.68  | 4486.12  | 0.87     |

Top Insights:
- Smoking and BMI are the strongest predictors of insurance costs.
- Ensemble models outperform Linear Regression for non-linear relationships.
- Gradient Boosting slightly outperforms Random Forest in handling extreme charges.

Conclusion
This project demonstrates end-to-end regression modeling, including preprocessing, multiple model evaluation, and feature importance analysis. The model can be used to predict insurance charges for new individuals.

