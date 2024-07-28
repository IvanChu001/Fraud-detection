Goal

The goal of this project is to build and evaluate machine learning models for detecting credit card fraud transactions based on historical data.

Dataset

The dataset used in this project is the Credit Card Fraud Detection Dataset from Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly unbalanced, with only 492 fraudulent transactions out of a total of 284,807 transactions. The dataset has been pre-processed and contains only numerical input variables which are the result of a PCA transformation.

Notebook Structure

1.Data Loading and Preparation: The dataset is loaded from a CSV file, and necessary libraries are imported.
Exploratory Data Analysis (EDA): The dataset is explored, and various visualizations are created to understand the data distribution and correlations.

2.Data Preprocessing: The dataset is preprocessed, including handling missing values, scaling features, and splitting the data into training and testing sets.

3.Model Selection and Evaluation: Several machine learning models are trained and evaluated, including Logistic Regression, Decision Trees, Random Forest, and XGBoost. The models are evaluated using metrics such as accuracy, precision, recall, F1-score, and area under the ROC curve (AUC-ROC).

4.Model Tuning: Hyperparameter tuning is performed for the best-performing models using techniques like GridSearchCV and RandomizedSearchCV.

5.Final Model Selection and Evaluation: The best model is selected based on the evaluation metrics, and its performance is reported.
