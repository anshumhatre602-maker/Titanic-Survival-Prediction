Titanic Survival Prediction

Project Overview
This project predicts whether a passenger survived the Titanic disaster using machine learning techniques. It follows a complete data science workflow including data preprocessing, visualization, feature engineering, and model building.

Objective
The objective of this project is to analyze the Titanic dataset and build a predictive model that determines passenger survival based on various features.

Dataset
The dataset used is the Titanic dataset, which contains information such as:

Passenger Class (Pclass)
Gender (Sex)
Age
Number of siblings/spouses aboard (SibSp)
Number of parents/children aboard (Parch)
Fare paid
Embarkation port (Embarked)
Survival status (Survived)

Data Preprocessing

Handled missing values in Age and Embarked
Removed unnecessary columns such as Cabin, Name, and Ticket
Converted categorical features into numerical format
Created a new feature called FamilySize

Data Visualization
The following visualizations were created:

Survival count plot
Gender vs survival plot
Correlation heatmap

Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Machine Learning Model
Logistic Regression was used to classify whether a passenger survived or not.

Model Evaluation

Accuracy: approximately 80%
Confusion Matrix
Classification Report

How to Run the Project

Clone the repository
Open the project folder
Run the Jupyter Notebook file titanic.ipynb

Results and Insights

Female passengers had higher survival rates
Passengers in higher class had better survival chances
Fare and family size influenced survival

Future Improvements

Use advanced models such as Random Forest or XGBoost
Improve feature engineering
Perform hyperparameter tuning

Acknowledgement
This project was developed as part of a data science learning exercise.
