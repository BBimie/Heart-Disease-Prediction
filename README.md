# SCA-Mentoring-final-project
Final project required for the completion of the 3 months (Jan - March, 2020) SheCodeAfrica Mentoring Program

## Introduction
World Health Organization has estimated 12 million deaths occur worldwide, every year due to Heart diseases. Half the deaths in the United States and other developed countries are due to cardio vascular diseases. The early prognosis of cardiovascular diseases can aid in making decisions on lifestyle changes in high risk patients and in turn reduce the complications. This research intends to pinpoint the most relevant/risk factors of heart disease as well as predict the overall risk using logistic regression.


## Source of Data

The dataset is publically available on the Kaggle website, and it is from a cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a <b>10-year risk of future coronary heart disease (CHD)</b>.

## Data

The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.
Variables
Each attribute is a potential risk factor. There are both demographic, behavioral and medical risk factors.

Demographic:

- Sex: male or female(Nominal)
- Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)

Behavioral
- Current Smoker: whether or not the patient is a current smoker (Nominal)
- Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)

Medical( history)
- BP Meds: whether or not the patient was on blood pressure medication (Nominal)
- Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
- Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
- Diabetes: whether or not the patient had diabetes (Nominal)

Medical(current)
- Tot Chol: total cholesterol level (Continuous)
- Sys BP: systolic blood pressure (Continuous)
- Dia BP: diastolic blood pressure (Continuous)
- BMI: Body Mass Index (Continuous)
- Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
- Glucose: glucose level (Continuous)

Predict variable (desired target)
- 10 year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”)

### Projects
I worked on this topic two separate times, the preliminary data modelling can be found in **heart.ipynb**. I used Logistic regression model for prediction here.

I took a second look at the project when I learned more about machine learning, and I applied more predictive models to my data and also used different evaluation merics to see exactly how well my models performed, you can see that in **comparing different models.ipynb**
 
A technical article explaining the first project has been published on medium here:
https://medium.com/@babatolatemi/heart-disease-prediction-a-logistic-regression-implementation-from-python-scikit-learn-c4eb391a873f

Another techical article detailing the processes used in the second project, can be found here:
https://medium.com/@babatolatemi/a-second-look-into-heart-disease-prediction-53c262476607
