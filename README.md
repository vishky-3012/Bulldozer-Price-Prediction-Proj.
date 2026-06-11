# 🚜 Bulldozer-Price-Prediction-Proj.

This project focuses on predicting the sale price of bulldozers using historical auction data and machine learning techniques. The dataset contains information about machine specifications, usage details, auction records, and sale prices.

The data was cleaned and preprocessed by handling missing values, creating missing-value indicators, encoding categorical features, and extracting useful date-based features from the sale date. After preprocessing, a Random Forest Regressor was trained to learn patterns in the data and estimate bulldozer prices.

Hyperparameter tuning was performed using RandomizedSearchCV to improve model performance. The model was evaluated using metrics such as Mean Absolute Error (MAE), Root Mean Squared Log Error (RMSLE), and R² Score.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Objective
To build a machine learning model capable of predicting bulldozer sale prices based on historical auction and equipment data.
