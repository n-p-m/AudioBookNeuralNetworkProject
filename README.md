# Audiobook Customer Retention Prediction
📚 Overview
In this project, we aim to create a machine learning algorithm that predicts whether a customer will make another purchase from an Audiobook company based on their historical data. By focusing our efforts on customers who are likely to convert again, we can optimize advertising spending and identify growth opportunities.

📊 Dataset
The dataset is provided in a .csv file and contains the following variables for each customer:
* Customer ID: Unique identifier for each customer
* Book length in mins_avg: Average book length of all purchases (in minutes)
* Book length in minutes_sum: Total sum of book length of all purchases (in minutes)
* Price Paid_avg: Average price paid for all purchases
* Price paid_sum: Total sum of price paid for all purchases
* Review: A Boolean variable indicating if the customer left a review
* Review (out of 10): Rating given by the customer (out of 10)
* Total minutes listened: Total minutes the customer has listened to audiobooks
* Completion: Ratio of completion (from 0 to 1)
* Support requests: Number of support requests made by the customer
* Last visited minus purchase date: Number of days between the last visit and the last purchase date

🎯 Problem Statement
The goal is to predict whether a customer will buy again within the next 6 months based on their activity and engagement over the last 2 years. This is a binary classification problem, where the target variable is represented by 0 (won't buy) or 1 (will buy).

🔍 Approach
1. Data Preprocessing:
  * Handle missing values
  * Encode categorical variables
  * Scale numerical features
  * Split the data into training and testing sets
  
2. Model Selection:
  * Explore various classification algorithms (e.g., Logistic Regression, Decision Trees, Random Forest, XGBoost)
  * Evaluate model performance using appropriate metrics (e.g., accuracy, precision, recall, F1-score)
  * Perform hyperparameter tuning to optimize the selected model
  
3. Model Training and Evaluation:
  * Train the selected model on the training data
  * Evaluate the model's performance on the testing data
  * Analyze the model's predictions and identify important features
  * Performed advanced techniques like early stopping mechanism to avoid overfitting which leads to high variance.
  
4. Insights and Recommendations:
  * Interpret the model's results and derive insights
  * Provide recommendations for customer retention strategies based on the model's findings

🚀 Results
* Achieved an accuracy of 93% in predicting customer repurchase behavior
* Deducted actionable recommendations for targeted marketing and customer engagement

🛠️ Technologies Used
* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Keras
* Tensorflow

📖 References
Udemy Course: Data Science: Deep Learning in Python([Link](https://www.udemy.com/course/data-science-deep-learning-in-python))
