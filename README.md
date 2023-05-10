# Overview
This project aims to build a machine learning model to detect fraudulent credit card transactions using a dataset containing only numerical input variables which are the result of a PCA transformation. The dataset contains features such as 'Time', 'Amount', and 'Class', where 'Time' is the seconds elapsed between each transaction and the first transaction in the dataset, 'Amount' is the transaction amount, and 'Class' is the response variable taking a value of 1 in case of fraud and 0 otherwise.
# Steps
Importing Libraries and Loading Data <br>
Checking Null values and Duplicates and Dropping Them <br>
Value Counts of the Output Class <br>
Exploratory Data Analysis (EDA) <br>
Scaling the Time and Amount using Standard Scaler <br>
Train-Test Split <br>
Training Model (Random Forest Model) <br>
SMOTE for Upsampling the Minority Class <br>
Training the Model on the Balanced Data  <br>
Confusion Matrix and Accuracy Score of both the Models <br>
# Conclusion
The final model achieved high accuracy in detecting fraudulent credit card transactions. By using the SMOTE technique, we were able to balance the data and improve the model's performance on the minority class. This project demonstrates the importance of data preprocessing, feature scaling, and selecting appropriate models to achieve high accuracy in detecting fraudulent transactions.
