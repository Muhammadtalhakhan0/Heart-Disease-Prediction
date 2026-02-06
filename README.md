# Heart Disease Prediction 
**1.Project Overview:**

This project builds a machine learning model to predict whether a person has heart disease based on medical data. The Heart Disease UCI Dataset from Kaggle is used, and this project was completed as part of an internship task.

**2.Dataset:**

- Source: Kaggle (Heart Disease UCI)
- File: heart_disease_uci.csv
- Target column: num (0 = No disease, >0 = Disease)

**3.Tools Used:**

Python, pandas, numpy, matplotlib, seaborn, scikit-learn

**4.Workflow:**

- Load and inspect the dataset
- Handle missing values
- Perform Exploratory Data Analysis (EDA)
- Convert categorical features to numeric (one-hot encoding)
- Split data into training and testing sets
- Train a Logistic Regression model
- Evaluate using Accuracy, Confusion Matrix, and ROC Curve
- Analyze important features

**5.Result:**

The Logistic Regression model achieved good accuracy on the test data, showing that it can effectively distinguish between patients with and without heart disease. The confusion matrix shows how many cases were correctly and incorrectly classified, while the ROC curve indicates that the model has a good ability to separate the two classes. Feature importance analysis shows that medical factors like age, chest pain type, heart rate, and cholesterol have a strong impact on the prediction.

**6.Conclusion:**

This project demonstrates a complete machine learning pipeline for heart disease prediction and shows how classification models can be used on real medical data in an internship-level project.
