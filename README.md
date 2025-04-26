# Breast Cancer Classification — Logistic Regression vs Random Forest
# Objective
The primary objective of this project is to build and evaluate classification models to predict breast cancer diagnosis using the Breast Cancer dataset from scikit-learn. The models used are:
- Logistic Regression
- Random Forest Classifier

# Dataset
The Breast Cancer Dataset from scikit-learn is used for this project. It includes:
- Features: 30 numeric attributes related to tumor characteristics.
- Target: Binary classification (0 = malignant, 1 = benign).

# Key Steps
1. Split the dataset into training and testing sets (80/20 split).
2. Train a Logistic Regression model.
3. Train a Random Forest model.
4. Evaluate and compare the performance of both models using metrics:
   - Accuracy
   - Precision
   - Recall
   - F1 Score

# Evaluation Metrics Explained
+ **Accuracy:**  Percentage of correctly predicted instances out of all instances.
+ **Precision:**  Of all positive predictions, how many are actually positive. Important when false positives are costly.
+ **Recall (Sensitivity):**  Of all actual positives, how many did the model predict correctly. Crucial in medical applications like cancer detection.
+ **F1 Score:**  Harmonic mean of Precision and Recall. Balances both concerns, especially useful with imbalanced data.

# Results

![alt img](https://github.com/Engr-Usman-Ali/Model-Building/blob/c773ff74585fd4f6a004e44d2444a2eec900a217/Capture.PNG)

# Why These Metrics?
+ Each metric provides a unique perspective on model performance. Accuracy is a general measure but can be misleading for imbalanced datasets. Precision focuses on minimizing false positives, while Recall ensures low false negatives. F1 Score is a balanced approach, combining the strengths of precision and recall.
+ For breast cancer diagnosis, these metrics help evaluate models holistically, accounting for both false positives (overdiagnosis) and false negatives (missed diagnosis).
