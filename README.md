### ***Classification-of-Patients-using-Logistic-Regression-Decision-Trees-Random-Forest-Classifier-and-KN*** #### 

***Introduction***:
Classification is a type of supervised learning algorithm that is used to predict a target variable by classifying the input data into two or more classes. In this project, I will focus on implementing different classification models for a given dataset with the objective of predicting the risk level of a patient's health condition.

***Dataset***:
The dataset contains information about patients' age, blood pressure (systolic and diastolic), blood sugar level, body temperature, heart rate, and risk level. The risk level is the target variable, which can take three values - low, moderate, or high. There are 1014 rows in the dataset.

***Methodology***:
Data Preprocessing: The first step is to preprocess the data by scaling it using StandardScaler and splitting it into training and testing sets using the train_test_split function. This step ensures that the features have similar ranges and that the models are trained on independent data.
Model Implementation: Next, four classification models are implemented: a. Logistic Regression: An instance of the LogisticRegression class with "class_weight" set as 'balanced' is created. Logistic Regression is a linear model that works well when there is a linear relationship between the features and the target variable. b. Decision Tree Classifier: An instance of the DecisionTreeClassifier class is created. Decision Trees are non-parametric models that work well when there is a non-linear relationship between the features and the target variable. c. Random Forest Classifier: An instance of the RandomForestClassifier class with the criterion set as 'gini' is created. Random Forest is an ensemble method that combines multiple decision trees to improve accuracy and reduce overfitting. d. K-nearest Neighbors (KNN): Two classifiers with k=5 and k=1 are created. KNN is a non-parametric model that works well when there are clusters in the data.
Model Evaluation: After implementing all the models, I evaluated their performance metrics like accuracy, precision, and confusion matrix. Accuracy measures the percentage of correct predictions made by the model. Precision measures the ratio of true positives to true positives plus false positives. The confusion matrix gives insights into the number of true positives, true negatives, false positives, and false negatives predicted by the model. I have also plotted the confusion matrix for all the models using the Seaborn heatmap function.
Conclusion: Finally, I have concluded the project by comparing the performance of all the models.

***Objective***:
The objective of this classification project is to implement different classification models for the given dataset and evaluate their performance metrics like accuracy, precision, and confusion matrix.

***Steps***:
1. Data Preprocessing
2. Model Implementation
3. Model Evaluation
4. Conclusion
