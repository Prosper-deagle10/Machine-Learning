# Diabetes Prediction Using Machine Learning (Hands-on Data Science Project)

## 🚀 Project Overview
 This project focuses on predicting diabetes using the PIMA Diabetes Dataset and a Support Vector Machine (SVM) classifier. The aim is to classify individuals as diabetic or non-diabetic based on several medical attributes.

# Key Steps in the Project

### 1. Data Collection and AnalysisThe dataset used in this project is the PIMA Diabetes Dataset. It consists of 768 rows and 9 columns, representing various medical attributes like pregnancies, glucose levels, blood pressure, skin thickness, insulin, BMI, diabetes pedigree function, and age. The target variable is the "Outcome," where 1 indicates diabetic and 0 indicates non-diabetic. A quick analysis revealed:
 - Non-diabetic cases: 500
 - Diabetic cases: 268

# 2. Data Preprocessing 
 To ensure effective model performance, the features were standardized using the StandardScaler from scikit-learn. The data was then split into training and testing sets with an 80-20 ratio using train_test_split.

# 3. Model Training
 The classifier chosen for this project is a Support Vector Machine with a linear kernel. The model was trained on the standardized training data, achieving:

 Training set accuracy: 78.66%

 Test set accuracy: 77.27%

# 4. Prediction System

A predictive system was developed to classify new data entries as diabetic or non-diabetic. For instance:

 Input: (4, 110, 92, 0, 0, 37.6, 0.191, 30)

 Prediction: Not diabetic.


# Tools & Libraries Used

 Python: The programming language used for the project.

 Libraries:

 pandas, numpy: For data analysis and manipulation.

 scikit-learn: For preprocessing, model building, and evaluation.

# Conclusion & Next Steps

This project demonstrates the power of SVMs for binary classification tasks. Although the current results are promising, there is room for improvement. Future steps could include:

 Experimenting with other algorithms like Random Forests or Neural Networks.
