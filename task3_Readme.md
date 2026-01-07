## Task 3: Linear Regression for Sales Prediction

### Description
Built a simple Linear Regression model to predict future sales using time-based features and promotional data.

### Dataset
- Source: Kaggle – Store Sales Time Series Forecasting
- File used: train.csv

### Steps Performed
- Loaded and cleaned the sales dataset
- Converted date column to datetime format
- Extracted time features (year, month, day)
- Handled missing promotion values
- Selected features such as date components and promotions
- Split the dataset into training and testing sets
- Trained a Linear Regression model
- Predicted sales on test data
- Evaluated model performance using regression metrics
- Visualized actual vs predicted sales
- Exported prediction results to Excel

### Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

### Model Evaluation
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score (used as regression accuracy)

### Output
- Linear_Regression_Sales_Prediction.xlsx

### Learning Outcomes
- Understanding regression modeling
- Feature selection and train-test splitting
- Evaluating regression models using R², MAE, and RMSE
- Hands-on experience with predictive analytics
