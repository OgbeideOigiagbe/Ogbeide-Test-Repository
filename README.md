# **Netflix Customer Churn and Engagement Prediction**



### Project Overview



This project focuses on predicting customer churn for a Netflix-style streaming service using machine learning models. The work includes exploratory data analysis (EDA), feature engineering, model evaluation, and summary insights.



### **Dataset**



Source: Netflix Customer Churn and Engagement Dataset

* Key Features:
* Watch time
* Subscription plan
* Engagement metrics
* Churn\_Status\_(Yes/No) as the target variable



### 

### **Exploratory Data Analysis (EDA)**



Data Cleaning:



* Handled missing values and renamed columns.





Outlier Analysis:



* Watch Time feature evaluated using boxplots.





Visualizations:



* Churn distribution plot.



* Feature correlation heatmap.





### **Modeling Approach**



Models Used:



* Logistic Regression



* Random Forest Classifier



* Gradient Boosting Classifier



* Voting Classifier (soft voting)





Evaluation Metrics:



* Primary Metric: ROC AUC Score (selected for its ability to handle imbalanced binary classification)



* Secondary Metrics: Precision, Recall, F1-score via classification report.





### **Results Summary**



* Models achieved ROC AUC scores between 0.51 and 0.54.



* No single model performed significantly better than others, suggesting potential for further feature engineering or class balancing.





### **Potential Next Steps**



* Experiment with class balancing techniques (e.g., SMOTE).



* Apply hyperparameter tuning for Random Forest and Gradient Boosting.



* Explore new feature creation using engagement data.



* Note: All analysis and modeling were completed in Jupyter Notebook and can be found in the attached project repository.







