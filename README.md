# Power_Usage_Prediction
Predicts Daily Power Usage (in kWh), based on Weather conditions

Accuracy achieved: 70.14426%<br />

**Files present:**

_engine.py_ - Source Code, Python3 File<br />
_power_usage_prediction_1.ipynb_ - Source Code with IPython magic commands, Jupyter Notebook<br />
_train_inputs.parquet, train_targets.parquet_ - Input columns and Target column DataFrames used for Training the models, Parquet Files<br />
_test_inputs.parquet, test_targets.parquet_ - Input columns and Target column DatFrames for Validation, Parquet Files<br />
_Model1.joblib_ - sklearn.LinearRegression() model, Joblib File<br />
_Model2.joblib_ - sklearn.SGDRegressor() model, Joblib File<br />

**Dependencies to be installed for using the model:**

pandas<br />
joblib<br />
