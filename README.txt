Overview


This project aims to develop a predictive model to forecast the bike rental count based on various features such as date, 
and time of the day,name of start with location ,name of end with location , duration , distance    .
The project utilizes hour datasets.
" The "day" dataset contains daily aggregated bike rental information,
while the "hour" dataset provides hourly details. Dataset Description Day Dataset


To run the project locally, following dependencies installed:

Python 3.7 or higher
NumPy
Pandas
Scikit-learn
Matplotlib
Jupyter Notebook
ipykernel


Results
The results of the bike sharing demand prediction are evaluated based on various metrics such as mean absolute error (MAE), root mean squared error (RMSE), and R-squared score. These metrics provide insights into the performance of the model and how well it predicts bike sharing demand.



Model Building and Selection
To predict the bike rental count, several machine learning models were implemented and evaluated. The following algorithms were utilized:
Linear Regression
Random Forest
Lasso
Ridge
XGBoost
GradientBoostingRegressor
And deep leanrnig with tensorflow

After training and evaluating these models, XGBoost was chosen as the final model due to its superior performance in terms of accuracy and predictive power. Model Deployment

The selected XGBoost model was deployed using Streamlit, a Python library for building interactive web applications. The deployment allows users to input the relevant features such as date, weather conditions, and time, and obtain the predicted bike rental count as the output.


Conclusion
This project demonstrates the application of machine learning models in predicting bike rental counts. By leveraging the power of LightGBM and utilizing various input features, the model achieves accurate predictions, allowing users to make informed decisions related to bike rental management.
