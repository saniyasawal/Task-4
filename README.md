# Task-4
Task 4: Classification with Logistic Regression

I started by loading the dataset and dropped the column that had too many missing values. My target column had two labels, B (Benign) and M (Malignant), which I used for binary classification. I split the data into training and testing sets and standardized the features. Then I trained a Logistic Regression model on the dataset. After making predictions, I evaluated the model using a confusion matrix, classification report, and ROC curve. The ROC curve showed an AUC close to 1.0, which means the model is performing almost perfectly in distinguishing between benign and malignant cases.
