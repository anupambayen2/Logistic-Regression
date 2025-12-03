Project Summary: Customer Purchase Prediction Using Logistic Regression

This project applies Logistic Regression to predict whether a person will purchase a product based on their social network ad profile. It is part of my daily machine learning practice uploads on GitHub.

📌 Objective

To build a classification model that predicts whether a user will purchase a product based on two features:

Age

Estimated Salary

📊 Dataset

Dataset used: Social_Network_Ads.csv

Contains:

User ID

Gender

Age

Estimated Salary

Purchased (0 or 1)

The target variable is Purchased, which indicates whether the user bought the product.

🛠️ Steps Performed

Loaded and cleaned the dataset

Selected features (Age & Estimated Salary)

Split data into training and test sets

Applied Feature Scaling for Logistic Regression

Trained Logistic Regression model

Predicted user purchase probability

Evaluated model with:

Confusion Matrix

Accuracy Score

Visualization of decision boundaries

📈 Key Insight

Probability increases sharply for users with higher age and higher salary.

Logistic Regression draws a linear decision boundary to separate buyers and non-buyers.

Despite its simplicity, the model performs well on this binary classification task.

🧪 Outputs

Confusion Matrix

Accuracy Score

Decision boundary plot

Predicted class labels

🚀 Conclusion

Logistic Regression is a powerful and interpretable algorithm for binary classification.
It performs well on this dataset and provides clear insight into how Age and Salary influence buying decisions.
