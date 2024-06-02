# Heart-Disease-Predicition-using-ML

Prediciting heart disease using machine learning¶
This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of prediciting whether or not someone has heart disease based on their medical attributes.

We are going to take the following approach:

Problem Definiton
Data
Evaluation
Features
Modelling
Experimentation
1.Problem Definiton
In a statement,

Given clinical parameters about a patient, can we predict whether or not they have heart disease?

2.Data
The original data came from Cleavland data from the UCI Machine Learning Repository - https://archive.ics.uci.edu/dataset/45/heart+disease

There is also a version of it available on Keggle. https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

3.Evalation
If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll persure the project.

4.Features
This is where we get different information about each of the features in our data

Create data dictionary

id (Unique id for each patient)
age (Age of the patient in years)
origin (place of study)
sex (Male/Female)
cp chest pain type ([typical angina, atypical angina, non-anginal, asymptomatic])
trestbps resting blood pressure (resting blood pressure (in mm Hg on admission to the hospital))
chol (serum cholesterol in mg/dl)
fbs (if fasting blood sugar > 120 mg/dl)
restecg (resting electrocardiographic results)
-- Values: [normal, stt abnormality, lv hypertrophy]
thalach: maximum heart rate achieved
exang: exercise-induced angina (True/ False)
oldpeak: ST depression induced by exercise relative to rest
slope: the slope of the peak exercise ST segment
ca: number of major vessels (0-3) colored by fluoroscopy
thal: [normal; fixed defect; reversible defect]
num: the predicted attribute
