# 2024_HFT_exercise_2

We are given two time series csv files, "D1_Project_train.csv" and "D1_Project_test.csv". Each consists of 66 features and one additional column (which represents return) to predict. We want to generate a model which predicts the return value, and want to setup a trading strategy for each row. For example, for each test set row, from 66 features,

1) we predict the return value from these features
2) determine whether we will collect this row.

The final return will be the sum of actual return values we choose by this procedure. How can we maximize the return?

------------------- The size of the dataset -------------------

"D1_Project_train.csv" : 90000 * 67 / "D1_Project_test.csv" : 19707 * 67
time difference between rows are not given but provided they are all equal.
