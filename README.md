<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>


---

# Model Selection and Scaling for Predictive Analysis

## Overview
Once the data has been prepared for input into the machine learning model, the next step is to experiment with various models and scaling techniques. This allows us to determine the best combination for predicting the target feature based on the other variables.

## Steps

1. **Data Preparation**  
   Before model selection, the data should be cleaned and preprocessed to ensure it is ready for analysis. This includes handling missing values, encoding categorical variables, and splitting the data into training and test sets.

2. **Model Selection**  
   Test different machine learning models to evaluate their performance on the dataset. Some commonly used models include:
   - Linear Regression
   - Decision Trees
   - Random Forest
   - Support Vector Machines (SVM)
   - Gradient Boosting Models

3. **Feature Scaling**  
   Apply different scaling techniques to standardize or normalize the data. Common scaling methods include:
   - **StandardScaler**: Scales data to have a mean of 0 and a standard deviation of 1.
   - **MinMaxScaler**: Scales data to a specified range, typically between 0 and 1.
   - **RobustScaler**: Scales data using the median and interquartile range, making it less sensitive to outliers.

4. **Model Evaluation**  
   Use evaluation metrics, such as Mean Absolute Error (MAE), Mean Squared Error (MSE), or R-squared (for regression) to assess model performance. Select the best-performing model and scaling combination based on these metrics.

5. **Implementation**  
   Once the optimal model and scaling method have been determined, proceed to implement the model and tune it further if necessary.


## Deliverables

- `main.ipynb` with your responses.

## Submission

Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.

## Resources

[Linear Interpolation](https://en.wikipedia.org/wiki/Linear_interpolation)

[Missing Data Imputation](http://www.stat.columbia.edu/~gelman/arm/missing.pdf)

[7 Steps to Data Preparation](https://www.kdnuggets.com/2017/06/7-steps-mastering-data-preparation-python.html)

