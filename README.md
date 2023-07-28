## 🚀 Machine Learning: Student Performance Predictor

[![GitHub Classroom](https://img.shields.io/badge/GitHub_Classroom-Review_Assignment-41B883?style=for-the-badge&logo=github)](https://classroom.github.com/a/0IOmZycZ)
[![Visual Studio Code](https://img.shields.io/badge/Open_in_Visual_Studio_Code-Get_Started-007ACC?style=for-the-badge&logo=visual-studio-code)](https://classroom.github.com/online_ide?assignment_repo_id=11500776&assignment_repo_type=AssignmentRepo)

### 🎯 Overview

Welcome to the **Machine Learning for Student Performance Predictor**. This is a machine learning algorithm for predicting student performance using the Linear Regression technique. The goal of this program is to forecast the final grades of students based on their academic performance and other related factors.

In this algorithm, we use the "student-mat.csv" dataset, which is part of the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance). The dataset contains information about student performance in mathematics. The features include attributes such as first-period grade, second-period grade, weekly study time, school type, family size, parent's occupation, and more.


## Steps Performed by the Code

1. **Data Loading:** The code reads the "student-mat.csv" file, which contains the student performance data, using the pandas library. The data is loaded into a DataFrame for further processing.

2. **Data Preprocessing:** The dataset may have missing values or categorical variables that need handling. The code preprocesses the data, converting categorical variables into numerical form using one-hot encoding. This transformation is necessary because most machine learning algorithms, including Linear Regression, require numerical inputs.

3. **Data Splitting:** The data is split into training and testing sets using the `train_test_split()` function from sklearn. This ensures that the model is trained on a subset of the data and evaluated on unseen data to assess its generalization performance.

4. **Model Training:** The Linear Regression model from sklearn is created and trained on the training data using the `fit()` method. The model aims to learn the relationships between the features and the target variable (final grade).

5. **Model Evaluation:** After training, the model's performance is evaluated using the test data. Two common evaluation metrics used are Mean Squared Error (MSE) and R-squared (R2). MSE measures the average squared difference between the predicted and actual grades, while R2 indicates how well the model explains the variance in the target variable.

6. **Example Prediction:** The code algorithmnstrates how to make predictions for a new student using the trained model. You can input the first-period grade, second-period grade, and weekly study time of a new student, and the model will predict their final grade (G3).

### 📚 References

Cortez, Paulo. (2014). Student Performance. UCI Machine Learning Repository. [Link](https://doi.org/10.24432/C5TG7T)
