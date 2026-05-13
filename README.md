# developerHub_internship
there we have included task 1,2,3

# introduction
Welcome to my repository! This project is a collection of three distinct tasks that demonstrate my journey through the data science pipeline—from basic data exploration to advanced predictive modeling.

📌 Project Overview
This repository showcases the application of Python-based tools to solve real-world problems in three different domains: Biology, Finance, and Healthcare. Each task is designed to handle specific challenges like data cleaning, feature engineering, and model evaluation.

📂 What's Inside?
🌸 Iris Species Exploration (EDA): A fundamental dive into statistical analysis and data visualization. This task focuses on understanding patterns and relationships within the classic Iris dataset using Seaborn and Matplotlib.

📈 AAPL Stock Price Prediction (Regression): A move into time-series forecasting. Using yfinance to pull real-world market data, I implemented a Random Forest Regressor to predict the next day's closing price for Apple Inc. (AAPL) stocks.

🏥 Heart Disease Risk Assessment (Classification): A practical machine learning application in healthcare. Using a Kaggle dataset, I built a Logistic Regression model to classify heart disease risks, featuring an interactive script that takes user input for real-time predictions.

"Each task is self-contained with its own set of visualizations and performance metrics."

# task#1: Exploring and Visualizing a Simple Dataset 
This repository contains basic data exploration and visualization tasks performed on the classic Iris Dataset. The project demonstrates the use of Python libraries for data manipulation and visual insights.

Overview
In this project, I have performed Exploratory Data Analysis (EDA) to understand the relationship between different features of the Iris flower species (Setosa, Versicolor, and Virginica).

Tasks Included:
Data Loading & Inspection: Loading the dataset using Seaborn and checking its structure (shape, columns, and info).

Statistical Summary: Generating descriptive statistics to understand the distribution of data.

Data Visualization:

Scatter Plots: To visualize the correlation between Sepal Length and Sepal Width.

Histograms: To see the frequency distribution of all numerical features.

Box Plots: To detect outliers and understand the spread of the data.

Technologies Used Python

Pandas: For data handling.

NumPy: For numerical operations.

Matplotlib & Seaborn: For creating insightful visualizations.

Key Visualizations
The project generates several plots to help analyze the data:

Scatter Plot: Colors coded by species to show clear clusters.

Histograms: To analyze the variance in petal and sepal dimensions.

Box Plot: A bird's eye view of the dataset's range and median values.

to run it clone this repo...

# task 2: Predict Future Stock Prices (Apple) 
In this task, I built a predictive model to estimate the next day's closing price of AAPL (Apple) stocks using historical data.

Key Features:
Live Data Fetching: Used yfinance to pull 5 years of real-time stock market data.

Feature Engineering: Prepared the dataset by shifting the 'Close' price to create a 'Target' variable for supervised learning.

Model Selection: Implemented the Random Forest Regressor, an ensemble learning method known for its accuracy and robustness.

Time-Series Splitting: Unlike standard shuffling, I used a chronological split (80/20) to maintain the time-dependent nature of stock data.

Prediction: The model provides a specific price prediction for the next trading day.

Performance Metrics:
Mean Squared Error (MSE): Used to measure the average squared difference between estimated and actual values.

R-squared Score: Used to determine how well the model explains the variance in the data.

New Libraries Added:
yfinance: For financial data extraction.

Scikit-Learn: For model training, data splitting, and evaluation.

# task 3: Heart Disease Prediction 

This task focuses on a healthcare application using a Kaggle dataset to predict the likelihood of heart disease in patients based on various medical attributes.

Key Features:
Data Preprocessing: Handled missing values and used One-Hot Encoding (via pd.get_dummies) to convert categorical health data into numerical format for the model.

Exploratory Data Analysis (EDA):

Correlation Heatmap: To identify which medical factors (like age, cholesterol, etc.) are most related to heart disease.

Target Distribution: Visualizing the balance between healthy and heart disease cases.

Classification Model: Implemented Logistic Regression, a standard yet powerful algorithm for binary classification tasks.

Model Evaluation:

Confusion Matrix: To track True Positives, True Negatives, and Misclassifications.

ROC-AUC Curve: Used to measure the model's ability to distinguish between classes (Area Under Curve).

Feature Importance: A bar plot showing which health factors (e.g., chest pain type, vessels colored) most impact the prediction.

Interactive Prediction: Added a user-input system where you can manually enter patient details to get a real-time risk assessment.

Key Libraries:
Scikit-Learn: For the Logistic Regression pipeline and evaluation metrics.

Seaborn & Matplotlib: For advanced medical data visualization.

Pandas: For handling the Kaggle CSV data.

