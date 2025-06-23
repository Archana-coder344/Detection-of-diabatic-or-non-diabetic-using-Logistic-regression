#  Diabetes Prediction using Logistic Regression

Early detection of diabetes is critical for preventing complications and improving patient outcomes. This project aims to build a binary classification model that predicts the likelihood of diabetes based on input features such as glucose levels, BMI, age, and more.

- Logistic Regression is a supervised classification algorithm used for binary classification tasks. It outputs probabilities using the sigmoid function and applies a threshold (default = 0.5) to classify the output.

- Sigmoid Function: σ(z) = 1 / (1 + e^-z)


- Programming Language : Python
- Machine Learning : Scikit-learn
- Data Handling : Pandas, NumPy
- Visualization : Matplotlib, Seaborn
- Model Evaluation : Accuracy, precision ,recall, F1 Score Confusion Matrix, ROC-AUC

  Dataset
- Source: [PIMA Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Features: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age

Accuracy: 0.7532467532467533
Confusion Matrix:
 [[79 20]
 [18 37]]
Classification Report:
               precision    recall  f1-score   support

           0       0.81      0.80      0.81        99
           1       0.65      0.67      0.66        55

    accuracy                           0.75       154
   macro avg       0.73      0.74      0.73       154
weighted avg       0.76      0.75      0.75       154

- Confusion Matrix
<img width="497" alt="Confusion matrix" src="https://github.com/user-attachments/assets/04cd6b7d-a237-430c-b1c2-5d72748b808e" />

-ROC Curve
<img width="533" alt="ROC-Curve" src="https://github.com/user-attachments/assets/92f882cd-5e23-4f04-af3c-ac729a54572c" />





