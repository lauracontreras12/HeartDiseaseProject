# Heart Disease Project
Exploratory Analysis and Model Building for a Heart Disease Dataset

# Purpose

The purpose of this project is to see if we can properly predict whether a patient will have a heart disease or not and see which of the 4 models are the best to predict this outcome. 
* RandomForestClassifier
* LogisticRegression
* DecisionTreeClassifier
* KNClassifier 


# Dataset
The dataset used in this project was obtained from Kaggle.

https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

The dataset was created by combining different datasets that were already available, but had not been combined before. They were combined over 11 common features , making the final dataset at 918 observations.

* Age: age of the patient [years]
* Sex: sex of the patient [M: Male, F: Female]
* ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
* RestingBP: resting blood pressure [mm Hg]
* Cholesterol: serum cholesterol [mm/dl]
* FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
* RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
* MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
* ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
* Oldpeak: oldpeak = ST [Numeric value measured in depression]
* ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
* HeartDisease: output class [1: heart disease, 0: Normal]
