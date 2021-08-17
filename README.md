# Power_Usage_Prediction
Predicts Daily Power Usage (in kWh), based on Weather conditions

Accuracy achieved: 70.14426%<br />

**Files present: **

engine.py - Source Code, Python3 File<br />
power_usage_prediction_1.ipynb - Source Code with IPython magic commands, Jupyter Notebook<br />
train_inputs.parquet, train_targets.parquet - Input columns and Target column DataFrames used for Training the models, Parquet Files<br />
test_inputs.parquet, test_targets.parquet - Input columns and Target column DatFrames for Validation, Parquet Files<br />
Model1.joblib - sklearn.LinearRegression() model, Joblib File<br />
Model2.joblib - sklearn.SGDRegressor() model, Joblib File<br />

**Dependencies to be installed for using the model: **

pandas<br />
joblib<br />
