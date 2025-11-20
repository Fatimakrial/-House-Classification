# -House-Classification
This project focuses on developing machine learning models to estimate housing prices based on a wide range of property features. It is divided into two main components:

Classification: Determining whether a house falls into the “expensive” category.

Regression: Predicting the exact price of a house.

The overall workflow includes problem understanding, exploratory analysis, data cleaning, preprocessing, model building, and performance evaluation. The goal is to produce accurate and interpretable predictions that can support real-world decision-making.

🔹 Classification Approach

The classification phase began with establishing a simple baseline model to understand the difficulty of the task.
From there, more advanced models were introduced, including decision trees and other common classifiers.

Key steps included:

Handling numerical, ordinal, and nominal features appropriately

Encoding categorical data (using methods such as one-hot encoding)

Scaling and transforming features

Building an end-to-end pipeline to automate preprocessing and model training

Using hyperparameter tuning to improve performance

🔹 Regression Approach

For the regression phase, several algorithms were tested to estimate continuous house prices, such as:

Decision tree-based models

Random forest regressors

Linear and regularized regression models

Model performance was evaluated using metrics like R² and RMSE, with additional experiments focused on improving accuracy through:

Feature selection (K-Best, RFE, variance-based methods)

Comparing preprocessing strategies

Analyzing prediction errors and model behavior
