# Predicting-Employee-Attrition

## Objective
Using machine learning to predict employee attrition in Python.

## Data Description 
The dataset comprises 25,491 observations and encompasses 10 variables. Each row corresponds to an employee, with each column containing attributes associated with the employees:

* Work_accident (Indicates whether the employee experienced a workplace accident)
* last_evaluation (Time elapsed since the last evaluation in years)
* sales (Department in which the employee works)
* average_monthly_hours (Average monthly hours spent at the workplace)
* left (Indicates whether the employee departed from the workplace or not (1 or 0))
* number_projects (Number of projects completed during employment)
* satisfaction_level (Scale: 0–1)
* salary (Relative salary level)
* time_spend_company (Duration of employment at the company in years)
* promotion_last_5years (Indicates whether the employee received a promotion in the last five years)

## Approach
We perform turnover analysis project by using Python’s Scikit-Learn library. I have used Decision Tree, Gradient Boosting Regressor for calculating Accuracy and have obtained 96.35% and 97.1% respectively.

## Conclusion
Employees are leaving because of low salary, low promotion rate, higher number of projects and whose experience is close to 5 <br>
We have identified different clusters of employees<br>
We have identified the most important feature as **satisfaction level** from correlation matrix and also from decision tree <br>
Also we have built a model with good accuracy and precision indicating that the model can accuractely predict if the employee will leave the company or not<br>
<hr>

If you like this repo, please don't forget to give a ⭐.
