# Heart-Attack-China
This project focuses on analyzing a heart attack dataset from China and applying machine learning models to predict heart attack risks. The workflow includes Exploratory Data Analysis (EDA), logistic regression, decision tree classifier, and random forest classifier to identify key risk factors and improve predictive performance.

# Dataset
The dataset contains patient medical records and risk factors associated with heart attacks.
Features include demographic details, lifestyle habits, medical history, and health indicators.
The target variable represents the presence or absence of a heart attack.

# Exploratory Data Analysis (EDA)
Data Cleaning: Handled missing values, duplicates, and outliers.
Feature Distribution: Visualized numerical and categorical distributions.
Correlation Analysis: Identified relationships between features using heatmaps and statistical tests.
Feature Engineering: Created meaningful derived features where necessary.

# Machine Learning Models
1️⃣ Logistic Regression
Applied as a baseline model for binary classification.
Evaluated using accuracy, precision, recall, F1-score, and ROC-AUC.
2️⃣ Decision Tree Classifier
Trained a decision tree model to capture non-linear relationships.
Fine-tuned hyperparameters (max depth, min samples split).
3️⃣ Random Forest Classifier
Implemented an ensemble model to enhance performance.
Feature importance analysis to understand key predictors.

# Model Evaluation
Compared models based on confusion matrix, classification report, and AUC-ROC curves.
Random Forest outperformed other models with higher accuracy and recall.

# Key Findings & Conclusion
High-risk factors include [mention top risk factors from feature importance].
Random Forest provided the best performance for heart attack prediction.
Potential improvements: More feature engineering, hyperparameter tuning, or testing additional models.

# Tech Stack
Python (pandas, numpy, scikit-learn, matplotlib, seaborn)
Jupyter Notebook for EDA & model training
