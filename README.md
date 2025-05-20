# Diabetes-Prediction-Future-Risk-Prediction
A machine learning model to Predict Diabetes and Future risk.
This project implements a machine learning model to predict whether a person is diabetic based on clinical features,and if they are currently non-diabetic,it goes one step further to predict their future risk of developing diabetes within the next 5 years.

1.Diabetes Classification Model
Uses clinical inputs such as glucose level, BMI, age, etc., to determine if the individual currently has diabetes.

2.Future Risk Prediction
If the person is predicted to be non-diabetic,a separate model estimates the probability (%) of them developing diabetes in the near future (e.g., 5 years).
* Feature Engineering
Includes advanced features like:
AgeSquared,BMIChange,Glucose×Age Interaction,Future-projected age (AgePlusYears)

3.Trained Models
Logistic Regression, Random Forest, SVM and Decision Tree are compared and The best-performing model is saved and used for predictions.

4.Interactive User Interface(with ipywidgets)
Displays instant prediction and future risk score.
