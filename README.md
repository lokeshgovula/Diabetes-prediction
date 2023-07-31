# Diabetes-prediction
Binary Classification Model for Prediction of Presence of Diabetes
## Objective:

The objective of this analysis is to develop a predictive model that can accurately determine the presence or absence of diabetes based on a set of variables. The dataset contains information on nine variables, including the target variable, which is the presence or absence of diabetes. The remaining eight variables are gender, age, hypertension, heart disease, smoking history, BMI, HbA1c level, and blood glucose level.

Identify key risk factors: Determine which variables have the strongest association with diabetes. Investigate the impact of gender, age, hypertension, heart disease, smoking history, BMI, HbA1c level, and blood glucose level on the likelihood of having diabetes. This analysis will provide insights into the risk factors associated with diabetes and their relative importance.

Developing a model that can accurately predict whether an individual has diabetes based on the given variables. The model will be trained using the available data and evaluated for its performance in terms of accuracy, precision, recall, and other relevant metrics.

Evaluate model performance of the predictive model using appropriate validation techniques such as cross-validation or holdout validation. Measure the model's accuracy, precision, recall, and F1 score to ensure its reliability and generalizability.

This knowledge can help in early detection, prevention, and management of diabetes, ultimately leading to improved healthcare outcomes and quality of life.


## Data Description


Contains 9 variables including target variable 

The target variable is diabetes

Remaining 8 variables are : 

Gender : Gender refers to the biological sex of the individual, which can have an impact on their susceptibility to diabetes. There are three categories in it male ,female and other. 

Age : Age is an important factor as diabetes is more commonly diagnosed in older adults.Age ranges from 0-80 in our dataset.

Hypertension : Hypertension is a medical condition in which the blood pressure in the arteries is persistently elevated. It has values a 0 or 1 where 0 indicates they don’t have hypertension and for 1 it means they have hypertension.

Heart disease : Heart disease is another medical condition that is associated with an increased risk of developing diabetes. It has values a 0 or 1 where 0 indicates they don’t have heart disease and for 1 it means they have heart disease.

Smoking history : Smoking history is also considered a risk factor for diabetes and can exacerbate the complications associated with diabetes.In our dataset we have 5 categories i.e not current,former,No Info,current,never and ever.

BMI : BMI (Body Mass Index) is a measure of body fat based on weight and height. Higher BMI values are linked to a higher risk of diabetes. The range of BMI in the dataset is from 10.16 to 71.55. BMI less than 18.5 is underweight, 18.5-24.9 is normal, 25-29.9 is overweight, and 30 or more is obese. 

HbA1c HbA1c (Hemoglobin A1c) level is a measure of a person's average blood sugar level over the past 2-3 months. Higher levels indicate a greater risk of developing diabetes. Mostly more than 6.5% of HbA1c Level indicates diabetes. 

Blood glucose level : Blood glucose level refers to the amount of glucose in the bloodstream at a given time. High blood glucose levels are a key indicator of diabetes.

Target Variable(diabetes) : Diabetes is the target variable being predicted, with values of 1 indicating the presence of diabetes and 0 indicating the absence of diabetes.




## Summary:

we can conclude that HbA1c Level plays a very important role in deciding the presence of diabetes.

Apart from that, Blood Glucose Level, BMI, Age also are among the top contributors. 

On the other hand, factors such as  Hypertension, Gender, Heart disease and Smoking history tend not to contribute as significantly 

The presence of Diabetes can focus on variables that contribute significantly in determining if an patient is having Diabetes or not .  

Such variables are:

HbA1c Level

Blood Glucose Level

BMI

Age

The model trained with Gradient Boosting Classifier algorithm

Gradient Boosting Classifier : Accuracy 97.65% , Recall – 67%, Precision- 100%, Specificity- 100%

## Author 

Connect on [LinkedIN](https://www.linkedin.com/in/lokeshgovula/)

## License

[MIT License](LICENSE)

