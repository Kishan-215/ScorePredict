# ScorePredict

This project aims to predict student scores based on the number of hours they study using linear regression, a fundamental machine learning technique.

## Objective

The goal is to create a predictive model that estimates a student's score given the number of hours they studied.

## Steps Involved

1. **Data Preparation:**
   - A dataset containing study hours and corresponding scores is created and converted into a pandas DataFrame.

2. **Data Splitting:**
   - The data is divided into training and testing sets to evaluate the model's performance.

3. **Model Training:**
   - A linear regression model is created and trained using the training set.

4. **Prediction:**
   - The trained model is used to predict scores for the test set.

5. **Evaluation:**
   - Model performance is evaluated using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.

6. **Visualization:**
   - A scatter plot of the data points and the regression line is generated to visualize the model fit.

7. **Prediction Function:**
   - A function is provided to predict the score based on the number of study hours.

## Key Outputs

- **Model Evaluation Metrics:**
  - Mean Absolute Error (MAE): 4.18
  - Mean Squared Error (MSE): 21.60
  - Root Mean Squared Error (RMSE): 4.65
  - R² Score: 0.95 (indicating a high level of prediction accuracy)

- **Visualization:**
  - A plot showing the relationship between study hours and scores, with the regression line indicating the model's predictions.

- **Prediction Example:**
  - For 9.25 hours of study, the predicted score is approximately 93.69%.
