White Wine Quality Prediction using Machine Learning

Project Overview

White Wine Quality Prediction is a Machine Learning project that aims to predict the quality of white wine based on its physicochemical properties using Linear Regression.

The project uses data analysis, visualization, and machine learning techniques to understand the relationship between different wine characteristics and wine quality.

The main objective is to build a regression model that predicts wine quality and evaluates its performance using standard evaluation metrics.

Project Objectives

The main objectives of this project are:

- Understand and analyze the White Wine Quality dataset.
- Perform Exploratory Data Analysis (EDA).
- Identify relationships between wine features and quality.
- Visualize important patterns using graphs.
- Build a Linear Regression model.
- Evaluate model performance using MAE, MSE, and R² Score.
- Visualize actual and predicted quality values.
- Analyze prediction errors using residual visualization.

Dataset

Dataset: White Wine Quality Dataset

The dataset contains physicochemical properties of white wine samples along with their quality ratings.

It includes numerical features that help analyze wine characteristics and predict quality.

Key Features

Some important features include:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality

Target Variable: Quality

The quality column is used as the target variable for prediction.

Tools and Technologies

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Machine Learning
- Linear Regression

Project Workflow

The project follows a structured Machine Learning workflow:

1. Dataset Loading: Load the White Wine Quality dataset using Python.
2. Data Inspection: Examine dataset structure, columns, data types, and sample records.
3. Exploratory Data Analysis (EDA): Analyze the dataset and understand feature distributions.
4. Data Visualization: Create graphs to understand relationships between features.
5. Data Splitting: Divide the dataset into training and testing data.
6. Model Training: Train a Linear Regression model using training data.
7. Model Prediction: Predict wine quality using test data.
8. Model Evaluation: Evaluate predictions using MAE, MSE, and R² Score.
9. Visualization: Create Actual vs Predicted and Residual plots.
10. Conclusion: Summarize the model performance and project findings.

Machine Learning Algorithm

Linear Regression

Linear Regression is a supervised Machine Learning algorithm used to predict continuous numerical values.

In this project, Linear Regression is used to predict white wine quality based on its physicochemical properties.

The model learns the relationship between input features and the target quality value.

Model Evaluation

The model performance was evaluated using the following metrics:

Evaluation Metric| Result
Mean Absolute Error (MAE)| 0.586
Mean Squared Error (MSE)| 0.569
R² Score| 0.265

Evaluation Metrics Explanation

- MAE: Measures the average absolute difference between actual and predicted values.
- MSE: Measures the average squared difference between actual and predicted values.
- R² Score: Measures how much variation in the target variable is explained by the model.

The R² score of 0.265 indicates that the model explains approximately 26.5% of the variation in wine quality.

Data Visualization

The following visualizations were created as part of the project:

1. Actual vs Predicted Graph

This scatter plot compares actual wine quality values with the values predicted by the Linear Regression model.

It helps understand the prediction performance of the model.

2. Residual Visualization

The residual plot displays the difference between actual and predicted quality values.

Residual = Actual Value - Predicted Value

It helps identify prediction errors and analyze model performance.

Conclusion

This project predicts white wine quality using the Linear Regression Machine Learning algorithm.

The dataset was analyzed and visualized using Exploratory Data Analysis techniques.

A Linear Regression model was trained using training data and evaluated using test data.

The model performance was measured using MAE, MSE, and R² Score. Actual vs Predicted and Residual plots were also used to understand prediction performance and errors.

This project helped demonstrate the practical application of Machine Learning in predicting white wine quality.

Limitations

- The model uses Linear Regression only.
- The R² score indicates that the model has limited explanatory power.
- Prediction accuracy can be improved using feature selection and other regression algorithms.
- Wine quality ratings may depend on several complex factors.

Future Improvements

- Apply Random Forest Regression.
- Try Decision Tree Regression.
- Improve model performance through feature selection.
- Perform hyperparameter tuning.
- Compare different regression algorithms.
- Improve prediction accuracy.

Repository Structure

White-Wine-Quality-Prediction/
│
├── ML.ipynb
├── winequality-white.csv
└── README.md

Note: Update the dataset filename in the repository structure if your actual file has a different name.

Author

Machine Learning Project

Project Title: White Wine Quality Prediction Using Linear Regression

Domain: Machine Learning

Language: Python
