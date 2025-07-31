# Credit_Risk_Loan_Default_Prediction

Loan Default Risk Prediction
Machine Learning Model to Identify High-Risk Borrowers

Project Overview
Developed a Random Forest classifier achieving 94% accuracy (AUC: 0.98) to predict loan defaults, enabling lenders to mitigate financial risks through data-driven decisions.

Key Features
EDA Insights: Identified renters with high loan-to-income ratios (0.38 correlation) and elevated interest rates (0.34) as highest-risk segments.

Class Imbalance Fix: Applied SMOTE-ENN to boost minority class recall by 22% (69% → 91%).

Feature Importance: Top predictors: loan_percent_income (27% impact), person_income (18.5%), and loan_grade_D (13.3%).

Technology Used
Python Libraries: Scikit-learn, Pandas, Seaborn, imbalanced-learn

Methods: Logistic Regression (baseline), Random Forest, Hyperparameter Tuning (GridSearchCV)

Data Prep: Median imputation, one-hot encoding, feature scaling

🚀 Business Impact
Proposed risk-based pricing strategies for high-risk borrowers (e.g., renters).

Potential to reduce defaults by 15% through targeted interventions.
