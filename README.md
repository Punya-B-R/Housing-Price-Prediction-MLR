# Multiple Linear Regression Model for Housing Price Prediction
The project follows a structured approach to build a regression model:

1. Data Reading and Visualization: Load the dataset and visually explore the data to understand the relationships and trends.
Data Preparation: Prepare the data for modeling, which includes handling categorical variables, adding dummy variables, and scaling features.
Model Building:
Bottom-Up Approach: Start with a single predictor and incrementally add variables to the model.
Feature Selection: After all variables have been included, manually eliminate features to optimize the model's performance.
Residual Analysis: Examine the residuals to assess any patterns that might affect the reliability of the predictions.
Prediction: Use the model to make predictions and evaluate its effectiveness.
Recursive Feature Elimination (RFE): Solve the same prediction problem using the RFE method to automate feature selection.
