Bank Marketing Analysis Report
Objective
The goal of this analysis is to evaluate a bank marketing campaign dataset to predict whether a customer will subscribe to a term deposit based on various features such as demographic and campaign details.

Data Summary
Key Features:
Age: Age of the customer.
Job: Type of job.
Marital: Marital status of the customer.
Education: Level of education.
Previous Outcome: Outcome of the previous marketing campaign (if any).
Target Variable:
Subscribed: Whether the customer subscribed to a term deposit (yes or no).
Preprocessing Steps
Handling Missing Values:
Checked for missing values and handled them appropriately (e.g., filled with mean/mode).
Categorical Encoding:
Converted categorical variables (e.g., job, marital, education) into numeric using one-hot encoding.
Feature Scaling:
Standardized numerical features to improve model performance.
Feature Selection:
Selected important features based on correlation and feature importance analysis.
Models Used
Logistic Regression
Random Forest
Gradient Boosting
Performance Metrics:
Accuracy
Precision
Recall
F1-Score
ROC-AUC
Key Insights
Feature Importance:
The previous campaign's outcome had the highest predictive power.
Age and duration of the current call were also significant predictors.
Model Performance:
Random Forest and Gradient Boosting outperformed Logistic Regression in accuracy and recall.
The best model was Gradient Boosting with an ROC-AUC score of 0.92.
Conclusion
The analysis indicates that customers who had a positive outcome in the previous campaign are more likely to subscribe again.
Age and call duration are critical features to focus on for future campaigns.
Gradient Boosting is recommended for predictive modeling due to its superior performance.
Next Steps
Optimize hyperparameters of the Gradient Boosting model for even better results.
Incorporate additional features (e.g., social media activity or customer spending patterns) if available.
Design future campaigns targeting customers based on their profiles and past interactions.
Note
For full implementation details, please refer to the bank_marketing_analysis.ipynb notebook.

