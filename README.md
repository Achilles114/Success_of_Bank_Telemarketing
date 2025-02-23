# Success_of_Bank_Telemarketing
Training a Classification ML model.

Motivation

This project aims to predict the success of bank telemarketing campaigns for term deposit subscriptions. By leveraging machine learning techniques, we can help banks optimize their marketing strategies and improve the efficiency of their telemarketing efforts.

Method and Results

Data Preprocessing

Handled missing values in categorical features (job, education, contact, poutcome)

Encoded categorical variables using LabelEncoder

Scaled numerical features using StandardScaler

Extracted month and day from the 'last contact date' feature

Feature Engineering

Applied polynomial features (degree=3) to capture non-linear relationships

Addressed class imbalance using SMOTE (Synthetic Minority Over-sampling Technique)

Model Selection and Training

We evaluated several machine learning models:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

After hyperparameter tuning, the best performing models were:

Random Forest Classifier (F1-macro score: 0.9152)

Best parameters: {'criterion': 'gini', 'max_depth': 3, 'n_estimators': 50}

Decision Tree Classifier (F1-macro score: 0.8688)

Best parameters: {'criterion': 'gini', 'max_depth': 3}

The final model chosen for prediction was Logistic Regression with hyperparameter tuning, achieving competitive performance while maintaining interpretability.
