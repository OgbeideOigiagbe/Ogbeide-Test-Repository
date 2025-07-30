# **Netflix Customer Churn and Engagement Prediction**



### Project Overview

This project focuses on predicting customer churn for a Netflix-style streaming platform using supervised machine learning techniques. It includes exploratory data analysis (EDA), data preprocessing, multiple classification models, and performance evaluation using appropriate metrics.

### **Dataset**

Source: Netflix Customer Churn and Engagement Dataset

Target Variable: churn_status_(Yes/No)

* Key Features:
* Subscription_Length_(Months)
* Customer_Satisfaction_Score_(1-10)
* Daily_Watch_Time_(Hours)  etc.


### **Methodology Changes*

Switched to a more domain-relevant dataset simulating Netflix user behavior.

Expanded modeling from a single classifier to include Logistic Regression, Random Forest, Gradient Boosting, and a Voting Ensemble.

Added correlation analysis to examine feature-target relationships and multicollinearity.

### 

### **Exploratory Data Analysis (EDA)**



Data Cleaning:

 * Removed missing values and dropped unnecessary columns (e.g., CustomerID).
 * Converted categorical variables to numerical using one-hot encoding.
 * Visualized:
    * Churn distribution
    * Outliers (e.g., Genre_Preference)
    * Correlation matrix between features and with the target variable



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







