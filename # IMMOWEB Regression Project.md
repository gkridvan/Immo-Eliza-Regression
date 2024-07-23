# IMMOWEB Regression Project




# Description
This project involves predicting house prices based on various features using multiple regression models. The dataset used contains information about house sales and features like location, type of sale, and flooding risk zone. The goal is to evaluate and compare the performance of several machine learning models including Random Forest, Linear Regression, Gradient Boosting, Support Vector Regression, and CatBoost for predicting house prices.

# Installation
To run this project, you'll need to set up your Python environment and install the required packages. The easiest way to install the dependencies is by using pip:


```
pip install pandas numpy scikit-learn catboost
```





# Usage

# Data Preparation:
Ensure you have the dataset file newdata.csv in your working directory.
Run the provided script to clean and preprocess the data. The script performs operations such as:
Dropping unnecessary columns.
Encoding categorical variables.
Saving the cleaned data to newdatalast.csv.
Model Training and Evaluation:



# The script trains and evaluates multiple regression models:
RandomForestRegressor
LinearRegression
GradientBoostingRegressor
SVR
CatBoostRegressor
For each model, it calculates the Root Mean Squared Error (RMSE) or Mean Absolute Error (MAE) to evaluate performance.




# Run the Script:

Execute the Python script to see the RMSE for each model and the MAE for the CatBoost model.


# Visuals
For more detailed visualizations, you can integrate plotting libraries like Matplotlib or Seaborn. 




# Model Performance Comparison:
Create a bar chart to compare RMSE across different models.







# Feature Importance:
Use bar charts to show feature importances for models like Random Forest and CatBoost.





# Contributors
Ridvan Gok - Project Lead and Developer
Contributions from the community are welcome. Please fork the repository and submit a pull request for any improvements or fixes.




# Timeline
Week 1: Data acquisition and preprocessing.
Week 2: Model training and initial evaluation.
Week 3: Model comparison and performance tuning.
Week 4: Final testing and documentation.



# Personal Situation
This project was developed as part of a personal initiative to enhance skills in machine learning and data analysis. Your feedback and suggestions are highly valued and will help in refining the models and approach.

