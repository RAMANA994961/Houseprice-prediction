🏠 House Price Prediction using Machine Learning

📌 Project Overview This project focuses on building an end-to-end machine learning regression system to predict house prices using real-world data. The goal is to analyze housing features, preprocess data, train multiple models, compare their performance, and identify the most important factors affecting house prices. The project uses the Kaggle House Prices dataset and compares a baseline Linear Regression model with an advanced Random Forest Regressor.

🎯 Problem Statement Predict the sale price of houses based on various features such as overall quality, living area, garage capacity, basement size, and year built. This is a supervised learning regression problem.

📊 Dataset Source: Kaggle – House Prices: Advanced Regression Techniques Link: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

Dataset Details train.csv → Used for training and evaluation test.csv → Used for final prediction Target variable: SalePrice

🛠️ Technologies Used Python Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook (Anaconda)

⚙️ Project Workflow Data loading and exploration, Handling missing values, Encoding categorical features, Feature scaling, Train-test split, Model training, Model evaluation, Model comparison, Feature importance analysis

🤖 Models Implemented Linear Regression (Baseline Model), Random Forest Regressor (Final Model)

📈 Model Evaluation Metrics Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R² Score

Performance Summary Model R² Score Linear Regression-- Lower Random Forest --Higher

📌 Random Forest outperformed Linear Regression with better accuracy and lower error.
