# **Breast cancer detection**

This project aimed the detection of breast cancer using the [Breast Cancer Wisconsin (Original) Data Set](http://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29).

For that purpose, a series of steps were followed:
1. Data cleansing
 - Correction missing values
2. Data visualization and analysis
 - Principal Component Analysis (PCA) for data visualization
3. Model selection with hyperparameters tuning
 - Random Forest Classifier
 - Support Vector Machine
 - Logistic Regression
 - Voting Classifier with the previously tuned models (following a [Kaggle Kernel](https://www.kaggle.com/yassineghouzam/titanic-top-4-with-ensemble-modeling))
4. Comparison between models and final observations
 
 
To solve this problem, the following Python packages were used:
 - Pandas
 - NumPy
 - Matplotlib and Seaborn
 - Scikit-learn