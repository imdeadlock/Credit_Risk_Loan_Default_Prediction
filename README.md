# Credit_Risk_Loan_Default_Prediction

🔍 Loan Default Prediction Using Logistic Regression & Random Forest
This project focuses on building a robust machine learning pipeline to predict loan default risk using real-world credit data. It compares the performance of Logistic Regression and Random Forest classifiers, with emphasis on class imbalance handling, feature impact analysis, and threshold tuning to optimize business-relevant metrics like recall and AUC.

📊 Key Highlights:
Exploratory Data Analysis (EDA):
Revealed that renters with high loan-to-income ratios and interest rates were most prone to default. Correlation and coefficient analysis guided feature importance and risk segmentation.

Class Imbalance Strategy:
Addressed 22% class imbalance using RandomOverSampler, leading to a +42% recall improvement in Logistic Regression and +23% gain in Random Forest recall for defaulters.

Model Performance:

Random Forest: 92% Accuracy, 0.93 ROC-AUC

Logistic Regression: 75% Accuracy, 0.87 ROC-AUC

Precision-Recall analysis and custom thresholds used to align with high-risk business contexts.

End-to-End Pipeline:

Missing value imputation

Categorical encoding

Feature scaling

Learning curves, ROC plots, and feature importance visualization

🚀 Business Impact
Proposed risk-based pricing strategies for high-risk borrowers (e.g., renters).

Potential to reduce defaults by 15% through targeted interventions.
