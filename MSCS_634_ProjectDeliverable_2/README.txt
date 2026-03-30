MSCS 634 – Deliverable 2: Regression Modeling and Performance Evaluation

Student Name: Nasser Hasan Padilla
Course: MSCS 634 – Data Mining
Date: March 2026

Overview

This project focuses on developing and evaluating regression models to predict student academic performance using the Student Performance dataset. The objective is to apply feature engineering techniques, build multiple regression models, and evaluate their performance using standard metrics and cross-validation.

Dataset

The dataset used in this project is the Student Performance dataset, which includes demographic, social, and academic attributes of students. The target variable for this analysis is the final grade (G3).

Data preprocessing included:

* Handling missing values
* Encoding categorical variables using one-hot encoding
* Creating additional features such as interaction terms and polynomial transformations

Feature Engineering

Feature engineering was applied to improve model performance. New features included:

* Interaction between study time and number of past failures
* Polynomial transformation of age

These engineered features helped capture more complex relationships in the dataset.

Models Implemented

Two regression models were developed and evaluated:

1. Linear Regression
   A baseline model used to establish a reference for performance.

2. Ridge Regression
   A regularized model used to reduce overfitting and improve generalization.

Model Evaluation

The models were evaluated using the following metrics:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R-squared (R2 Score)

Additionally, 5-fold cross-validation was used to assess how well the models generalize to unseen data.

Results

* Ridge Regression demonstrated more stable performance across cross-validation folds.
* Linear Regression performed well but showed slightly higher variance.
* Feature engineering improved predictive performance by capturing non-linear relationships.
* Regularization in Ridge Regression helped reduce the impact of multicollinearity.

Overall, Ridge Regression was identified as the better-performing model due to improved generalization and more consistent results.

Challenges

Several challenges were encountered during the project:

* Handling categorical variables required proper encoding to avoid model errors.
* Feature selection required experimentation to determine which transformations improved performance.
* Balancing model complexity and overfitting required careful evaluation using cross-validation.

Conclusion

This project demonstrated how regression modeling can be applied to predict student performance effectively. By combining feature engineering, model comparison, and cross-validation, it was possible to identify the most reliable model. Ridge Regression provided the best balance between accuracy and generalization.

Files Included

* notebooks/MSCS_634_Deliverable_2_Regression.ipynb
* data/student-mat.csv (optional)
* results/deliverable2_model_results.csv
