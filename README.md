# Customer-Churn-Prediction

Overview

Customer churn prediction is crucial for businesses offering subscription-based services. This project builds a machine learning model to predict whether a customer is likely to discontinue their subscription based on historical data. The project provides actionable insights into the key factors driving customer churn, enabling businesses to implement effective retention strategies.

Features

Data Preprocessing: Handling missing values, encoding categorical variables, and normalizing numerical features.

Exploratory Data Analysis (EDA): Identifying key patterns and correlations influencing churn.

Feature Engineering: Creating meaningful features to enhance model performance.

Model Training & Evaluation: Implementing and evaluating various machine learning models.

Interpretability: Identifying the most significant factors contributing to customer churn.

Dataset

The dataset used is Churn_Modelling.csv, which consists of:

Demographic details (e.g., age, gender, location)

Subscription details (e.g., tenure, plan type, payment method)

Usage patterns (e.g., number of logins, average session duration)

Customer support interactions

Data Preprocessing

Handling Missing Values: Applied imputation strategies to fill missing data.

Encoding Categorical Data: Used one-hot encoding and label encoding techniques.

Imbalanced Dataset Handling: Implemented oversampling techniques like SMOTE.

Feature Scaling: Standardized numerical features where required.

Model Development

Implemented and compared various classification models:

Logistic Regression

Support Vector Classifier (SVC)

K-Nearest Neighbors (KNN)

Decision Trees (DT)

Random Forest (RF)

Gradient Boosting Classifier (GBC)

Evaluated models using:

Accuracy

Precision, Recall, F1-score

ROC-AUC score

Results & Insights

Model Evaluation:

Accuracy and precision were computed for multiple models to identify the best-performing one.

A comparison table was generated to visualize model performance.

Best-Performing Model:

The model with the highest accuracy and precision was selected as the best-performing model.

Further fine-tuning and hyperparameter optimization can enhance its predictive power.

Key Factors Affecting Churn:

Feature importance analysis was not explicitly performed. Implementing SHAP values or tree-based feature importance (e.g., Random Forest, XGBoost) is recommended.

Potentially significant factors include tenure length, monthly charges, and customer support interactions.

Recommendations for Churn Reduction:

Implement targeted retention strategies based on predictive insights.

Offer personalized discounts or loyalty rewards to high-risk customers.

Improve customer support response times to enhance customer satisfaction.

Installation & Usage

Prerequisites

Ensure you have the following installed:

Python 3.x

Jupyter Notebook or Google Colab

Required Python libraries (install using the command below):

pip install pandas numpy scikit-learn matplotlib seaborn xgboost lightgbm imbalanced-learn

Running the Project

Clone the repository or download the notebook.

Load the dataset using pandas.

Perform data preprocessing including encoding and scaling.

Train and evaluate different models.

Interpret the results and generate insights.

Conclusion

This project successfully predicts customer churn using machine learning models, providing valuable insights for businesses to enhance customer retention strategies.

Contact

For any queries or contributions, feel free to reach out!


