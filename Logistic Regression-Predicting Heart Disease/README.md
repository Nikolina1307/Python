# Logistic Regression for Predicting 10-Year Risk of Coronary Heart Disease (CHD)

## Description

Logistic Regression is a statistical method used for modeling binary outcomes, particularly when the outcome is categorical and represents two classes, such as "Yes" or "No", "Success" or "Failure", etc. In the context of predicting the 10-year risk of coronary heart disease (CHD), logistic regression can be employed to analyze various risk factors and their impact on the likelihood of developing CHD.

### Why Logistic Regression?

Logistic regression is a popular choice for binary classification tasks due to its simplicity, interpretability, and effectiveness in modeling probabilities. It's well-suited for scenarios where the outcome variable is categorical, making it suitable for predicting whether a patient has a certain medical condition or not.

### Where it can be used?

Logistic Regression finds applications in various fields such as healthcare, finance, marketing, and social sciences. In healthcare, it can be used for predicting the likelihood of diseases, identifying risk factors, and assessing the effectiveness of treatments.

## Project Description

The task of this project is to create a logistic regression model to predict whether a patient has a 10-year risk of future coronary heart disease (CHD). The dataset provided is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. It contains over 4,000 records with 15 attributes.

### Variables

- **Sex:** Male or Female (Nominal)
- **Age:** Age of the patient (Continuous)
- **Current Smoker:** Whether or not the patient is a current smoker (Nominal)
- **Cigs Per Day:** The number of cigarettes smoked on average per day (Continuous)
- **BP Meds:** Whether or not the patient is on blood pressure medication (Nominal)
- **Prevalent Stroke:** Whether or not the patient had previously had a stroke (Nominal)
- **Prevalent Hyp:** Whether or not the patient is hypertensive (Nominal)
- **Diabetes:** Whether or not the patient has diabetes (Nominal)
- **Tot Chol:** Total cholesterol level (Continuous)
- **Sys BP:** Systolic blood pressure (Continuous)
- **Dia BP:** Diastolic blood pressure (Continuous)
- **BMI:** Body Mass Index (Continuous)
- **Heart Rate:** Heart rate (Continuous)
- **Glucose:** Glucose level (Continuous)

### Predict Variable (Desired Target)

- **10-year risk of coronary heart disease CHD:** Binary outcome where "1" means "Yes" and "0" means "No"

## Insights
- All attributes selected after the elimination process show Pvalues lower than 5% and thereby suggesting significant role in the Heart disease prediction.

- Men seem to be more susceptible to heart disease than women.Increase in Age,number of cigarettes smoked per day and systolic Blood Pressure also show increasing odds of having heart disease.

- Total cholesterol shows no significant change in the odds of CHD. This could be due to the presence of 'good cholesterol(HDL) in the total cholesterol reading.Glucose too causes a very negligible change in odds (0.2%)

- The model predicted with 0.88 accuracy. The model is more specific than sensitive.

- The Area under the ROC curve is 73.5 which is somewhat satisfactory. 

- Overall model could be improved with more data.

---

Feel free to explore the code in this repository for a detailed understanding of the model used for predicting 10-Year risk of coronary heart disease (CHD) . If you have any questions or suggestions, please don't hesitate to reach out.

### Happy analysing! ✌️📊🔍
