Insurance Risk Analytics Project
🎯 Objective

This project analyzes insurance risk data to understand claim behavior, evaluate risk drivers, and build predictive models for risk-based pricing.

🧠 Project Tasks
Task 1 — Exploratory Data Analysis (EDA)
Data cleaning and preprocessing
Univariate & bivariate analysis
Outlier detection
Risk and profitability insights
Task 2 — Data Version Control (DVC)
Implemented DVC pipeline
Tracked raw and cleaned datasets
Configured local remote storage
Ensured reproducibility of datasets
Task 3 — A/B Hypothesis Testing
Tested risk differences across:
Provinces
Zip codes
Gender
Margin (profitability)
Applied:
ANOVA
Chi-square tests
T-tests
Generated business insights for pricing strategy
Task 4 — Machine Learning Models

Built predictive models for claim severity:

Linear Regression
Random Forest Regressor
XGBoost Regressor
Evaluation Metrics:
RMSE
R² Score
Explainability:
SHAP analysis used to identify key risk drivers
Key features influencing claims:
RiskScore
VehicleType
CustomValueEstimate
Province
📊 Key Insights
Risk varies significantly across geography
Vehicle type strongly impacts claim severity
High-value vehicles generate higher expected losses
RiskScore is a strong predictor of claims
⚙️ Tech Stack
Python
Pandas, NumPy
Scikit-learn
XGBoost
SHAP
DVC
Git & GitHub Actions
🚀 How to Reproduce
git clone <repo-url>
cd insurance-risk-analytics
pip install -r requirements.txt
dvc pull

Run notebooks in order:

01_eda.ipynb
02_hypothesis_testing.ipynb
03_modeling.ipynb
