Key Components
1. Data Preprocessing
Missing Values: Any missing values in the total_bedrooms column are filled with the median value.
One-Hot Encoding: The categorical column ocean_proximity is transformed into numeric form using one-hot encoding.

2. Model Building
Two models are built and trained:
Linear Regression:
A simple model to predict housing prices based on the dataset’s features.
Decision Tree Regressor:
A non-linear model that uses tree-based decisions to make predictions.

3. Model Evaluation
The models are evaluated using the following metrics:
Root Mean Squared Error (RMSE): Measures the differences between predicted and actual house values.
R² Score: Indicates how well the model explains the variability of the target variable.

4. Visualization
A scatter plot is generated to visualize the relationship between actual and predicted house values for the Linear Regression model.

5.Results
Linear Regression:
RMSE and R² are calculated to assess the performance.
Decision Tree Regressor:
RMSE and R² are computed for comparison.
The results are printed to the console and displayed graphically.

