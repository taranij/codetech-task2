Name: TARANI J
Company: CODTECH IT SOLUTIONS
ID:CT4DS2852
Domain: Data Analysis
Duration:June 2024 to July 2024
Mentor: SANTHOSH KUMAR
Overview of the Simple Linear Regression Project:
<img width="1440" alt="Screenshot 2024-06-29 at 1 45 45 PM" src="https://github.com/taranij/codetech-task2/assets/174124687/52bf8650-ca38-4ae7-b7d9-26b748c35867">
<img width="1440" alt="Screenshot 2024-06-29 at 1 45 48 PM" src="https://github.com/taranij/codetech-task2/assets/174124687/82ba0cc0-2e4b-4610-a5b4-fefb234a2e6d">
<img width="1440" alt="Screenshot 2024-06-29 at 1 45 56 PM" src="https://github.com/taranij/codetech-task2/assets/174124687/25b2ca64-aa57-49e5-9ec4-56ea530a9cac">
<img width="1440" alt="Screenshot 2024-06-29 at 1 46 12 PM" src="https://github.com/taranij/codetech-task2/assets/174124687/1d4f64c6-1565-4ad2-aeb6-1d63e1cc9471">





 Objectives:
1. Implement a simple linear regression model using a dataset with continuous target variables.
2. Split the dataset into training and testing sets to validate the model.
3. Train the model on the training data.
4. Evaluate the model's performance using metrics like mean squared error (MSE) and R-squared.
5. Make prediction on the test set.
6. Visualize the regression line and the actual vs. predicted values to assess the model's accuracy.

Key Activities:
1. Data Loading:
   - Load the diabetes dataset from `sklearn.datasets`.
   - Select a single feature for simplicity.

2. Data Splitting:
   - Split the dataset into training and testing sets using `train_test_split` from `sklearn.model_selection`.

3. Model Training:
   - Create a linear regression model using `LinearRegression` from `sklearn.linear_model`.
   - Train the model on the training data.

4. Model Evaluation:
   - Make predictions on the test set.
   - Evaluate the model's performance using mean squared error (MSE) and R-squared metrics from `sklearn.metrics`.

5. Visualization:
   - Plot the regression line along with actual data points to visualize the model's fit.
   - Plot actual vs. predicted values to assess the model's accuracy.

Technologies Used:
- Python: The primary programming language used for the implementation.
- Numpy: For numerical operations.
- Matplotlib: For plotting and visualizations.
- Scikit-learn: For machine learning algorithms and tools.
-  Key Insights from the Simple Linear Regression Project:
1. Model Performance:
   - Successfully trained the linear regression model with meaningful performance metrics (MSE and R²), demonstrating the model's accuracy.

2. Importance of Data Splitting:
   - Splitting data into training and testing sets is essential for evaluating model generalization and preventing overfitting.

3. Feature Selection:
   - Using a single feature simplified the model but highlighted the limitations of capturing complex data patterns with one feature.

4. Visualization:
   - Visualizing the regression line and actual vs. predicted values provided intuitive insights into model fit and prediction accuracy.

5. Linear Relationship:
   - Linear regression effectively captured the linear relationship between the feature and the target variable but may require more features or complex models for non-linear relationships.

6. Model Limitations:
   - The simplicity of linear regression makes it easy to implement but may not capture all data nuances, suggesting potential improvements with more features or advanced models.

This project provides a basic yet comprehensive introduction to implementing, training, and evaluating a simple linear regression model using a well-known dataset.
