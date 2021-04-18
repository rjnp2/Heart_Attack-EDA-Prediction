# Heart_Attack-EDA-Prediction

Welcome to this project on Loan Prediction Practice Problem.

## Objective:

1. Introduction to the problem
2. Exploratory Data Analysis (EDA) and PreProcessing
3. Model building

## Description  
  To perform EDA and predict if a person is prone to a heart attack or not.
  
  Heart disease is the leading cause of death for people of most racial and ethnic groups. \
  One person dies every 37 seconds just in the United States alone from cardiovascular disease. \
  Complete analysis of Heart Disease UCI dataset both visually and statistically to obtain critical observations which can be used for inference. \
To predict whether a person has a heart disease or not based on the various biological and physical parameters of the body \
To make a model having high accuracy and precision and can predict the results with greater confidence. \
Make these predictions accessible to users and patients anywhere, anytime so that they can get complete picture of their Health \

## Dependencies
  Python
  kaggle - Heart Attack Analysis & Prediction Dataset
  pandas 
  sklearn

## Datasets and Inputs
1. Collecting Data \
  The data used for training and testing is the Heart Disease UCI downloaded from Kaggle. This database contains 14 attributes.

  ![1](https://github.com/rjnp2/Heart_Attack-EDA-Prediction/blob/main/images/1.png)

2. Exploratory Data Analysis \
It's a clean, easy to understand set of data. However, the meaning of some of the column headers are not obvious. Here's what they mean,

  - age: The person's age in years
  - sex: The person's sex (1 = male, 0 = female)
  - cp: The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)
  - trestbps: The person's resting blood pressure (mm Hg on admission to the hospital)
  - chol: The person's cholesterol measurement in mg/dl
  - fbs: The person's fasting blood sugar (&gt; 120 mg/dl, 1 = true; 0 = false)
  - restecg: Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)
  - thalach: The person's maximum heart rate achieved
  - exang: Exercise induced angina (1 = yes; 0 = no)
  - ldpeak: ST depression induced by exercise relative to rest ('ST' relates to positions on the ECG plot. See more here)
  - slope: the slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)
  - ca: The number of major vessels (0-3)
  - thal: A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect)
  - target: Heart disease (0 = no, 1 = yes)

