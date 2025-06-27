Overview:
This project presents a sales forecasting model for Walmart. The dataset was sourced from Kaggle and then various techniques were applied to analyse and drive meaningful insights from the data.

Dataset:
Duration: 2 Years
Stores: 45
Total Records: 421571
Collected Parameters: Store, Department, Date, Weekly_Sales, Is_Holiday

Libraries Used:
Python
Pandas, NumPy
Matplotlyb, Seaborn
Scikit-Learn
TensorFlow, Keras
Google Colab

Model Architecture:
Models Used: RandomForestRegressor, Long Short Term Memory (LSTM)
Optimizer: Adam Optimizer
Loss Function: Mean Squared Error
Accuracy: Random Forest achieved 61.5% accuracy, LSTM achieved 95.9% accuracy.

Results:
Random Forest didn't have good results, it failed to capture time-based trends in data. LSTM on the other hand achieved high accuracy, it even predicted peaks and dips even around holidays. And it will only get better with more predictions overtime regarding time series data.

Contact @rehanmuhammad9999@gmail.com