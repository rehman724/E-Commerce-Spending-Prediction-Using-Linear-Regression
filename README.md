# E-Commerce-Spending-Prediction-Using-Linear-Regression
## Project Overview
This project uses linear regression to predict the yearly amount spent by e-commerce customers based on demographic and behavioral data. The project involves data preprocessing, exploratory data analysis, model training, model evaluation, and model deployment.
## Requirements
- Python 3.x
- pandas
- NumPy
- seaborn
- matplotlib
- scikit-learn
- statsmodels
- scipy
- Pickle
## Methodology
### Data Preprocessing
- Loaded the e-commerce customer data from a CSV file
- Performed data cleaning and preprocessing, including handling missing values and duplicates
- Generated descriptive statistics for the data
### Exploratory Data Analysis (EDA)
- Created scatterplots and line plots to visualize the relationships between variables
- Calculated the correlation matrix for the numeric columns
- Created a heatmap to visualize the correlation matrix
### Model Training
- Split the data into training and testing sets
- Trained a linear regression model on the training data
- Used the trained model to make predictions on the testing data
### Model Evaluation
- Calculated the R-squared score, mean absolute error (MAE), mean squared error (MSE), and root mean squared error (RMSE) to evaluate the model's performance
- Created a scatter plot of the actual values versus the predicted values
### Model Deployment
- Serialized the trained model using pickle
- Made predictions on new data using the serialized model
## Conclusion
This project demonstrates the use of linear regression to predict e-commerce customer spending habits. The results show a good performance of the model, indicating its potential use in real-world applications.
