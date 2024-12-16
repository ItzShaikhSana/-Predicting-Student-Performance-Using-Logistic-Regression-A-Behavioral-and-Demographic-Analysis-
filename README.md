## **Predicting Student Performance Using Logistic Regression A Behavioral and Demographic Analysis**
_____________________________________________________________________________________________________

**Project Overview**

This project aims to classify student performance into different categories based on various factors, using a Logistic Regression model. The dataset includes attributes related to student demographics, behavior, and engagement. The objective is to build a classification system that predicts the class of a student (e.g., Low, Medium, High) based on their performance-related features.

**Dataset Information**

The dataset contains 480 records and 17 attributes with no missing values. The columns in the dataset are as follows:

**Feature Description**

gender - Gender of the student (categorical: Male/Female).

NationalITy - Nationality of the student (categorical).

PlaceofBirth - Place of birth of the student (categorical).

StageID - Educational stage of the student (categorical: Lower, Middle, High School).

GradeID - Grade of the student (categorical).

SectionID - Section ID of the student (categorical: A, B, C).

Topic - Subject/topic taught (categorical).

Semester - Semester of the academic year (categorical: First/Second).

Relation - Relation of the parent/guardian (categorical: Father/Mother).

raisedhands - Number of times the student raised their hand in class (numeric).

VisITedResources - Number of online resources visited by the student (numeric).

AnnouncementsView - Number of announcements viewed by the student (numeric).

Discussion - Number of times the student participated in discussions (numeric).

ParentAnsweringSurvey - Whether the parent answered the survey (categorical: Yes/No).

ParentschoolSatisfaction - Parent's satisfaction with the school (categorical: Good/Bad).

StudentAbsenceDays - Whether the student was frequently absent (categorical: Under-7 or Above-7 days).

Class - Performance class of the student (categorical: Low, Medium, High) (target).

**Objective**

The primary objective is to develop a Logistic Regression model to classify student performance into one of the three classes (Low, Medium, High) and identify the key factors influencing these classifications.

**Project Steps**

**Data Exploration**

1. Perform initial data analysis to understand the dataset.

2. Visualize feature distributions and relationships using plots (e.g., bar plots, box plots, pair plots).

**Data Preprocessing**

1. Encode categorical variables using techniques like one-hot encoding or label encoding.

2. Normalize/scale numeric variables.

3. Split the dataset into training and testing sets.

**Model Building**

1. Train a Logistic Regression model using the training dataset.

2. Tune hyperparameters to optimize model performance.

**Model Evaluation**

Evaluate the model using metrics such as:

1. Accuracy

2. Precision

3. Recall

4. F1-Score

5. Confusion Matrix

______________________________________________________________________________________________________________

**Key Insights:**

Features like raisedhands, VisITedResources, and Discussion show the strongest correlation with student performance.

Parental satisfaction and attendance (StudentAbsenceDays) are significant factors in predicting performance.

**Technologies Used**

**Programming Language:**

Python

**Libraries:**

pandas for data manipulation.

numpy for numerical computations.

matplotlib and seaborn for data visualization.

sklearn for machine learning modeling and evaluation.

statsmodels for statistical analysis.

**Future Work**

Test the model on larger, diverse datasets to evaluate its generalizability.

Experiment with advanced classification techniques such as Gradient Boosting and Neural Networks.

Deploy the model using Flask or Streamlit to provide real-time predictions.

Implement feature importance analysis to understand the contribution of each feature.

**Contributing**

Contributions are welcome! Please fork the repository and submit a pull request.




