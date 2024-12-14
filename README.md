Method :
Dataset Download: The dataset is read directly from the UCI Machine Learning repository using pandas.read_csv.
Diagnosis Conversion: The Diagnosis column is converted to -1 for benign and +1 for malignant.
Feature Matrix (P) and Target Vector (T): We extract the feature matrix P (all feature columns) and target vector T (the diagnosis values).
Print Statements: The code prints the few rows of P and T and also displays the dimensions of the data.
Note : TPR – True Positive Rate and FPR – False Positive Rate
