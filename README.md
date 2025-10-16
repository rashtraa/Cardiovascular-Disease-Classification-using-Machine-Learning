# Cardiovascular-Disease-Classification-using-Machine-Learning

Project Overview

This project aims to predict the presence of heart disease in patients using a machine learning model. By analyzing a dataset containing various medical attributes, we can build a classifier to determine whether a patient is likely to have heart disease. This can be a valuable tool for assisting healthcare professionals in diagnosing and treating cardiovascular conditions.

Dataset

The dataset used for this project is heart.csv. It contains 12 columns (features) and a target variable, HeartDisease.

Features:

Age: Age of the patient 

$$years$$

Sex: Sex of the patient 

$$M: Male, F: Female$$

ChestPainType: Chest pain type 

$$TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic$$

RestingBP: Resting blood pressure 

$$mm Hg$$

Cholesterol: Serum cholesterol 

$$mm/dl$$

FastingBS: Fasting blood sugar 

$$1: if FastingBS \> 120 mg/dl, 0: otherwise$$

RestingECG: Resting electrocardiogram results 

$$Normal: Normal, ST: having ST-T wave abnormality, LVH: showing probable or definite left ventricular hypertrophy$$

MaxHR: Maximum heart rate achieved

ExerciseAngina: Exercise-induced angina 

$$Y: Yes, N: No$$

Oldpeak: Oldpeak = ST

ST_Slope: The slope of the peak exercise ST segment 

$$Up: upsloping, Flat: flat, Down: downsloping$$

HeartDisease: Output class 

$$1: heart disease, 0: Normal$$

#How to Run This Project

Clone the repository:

git clone [https://github.com/YourUsername/heart-disease-prediction.git](https://github.com/YourUsername/heart-disease-prediction.git)



Navigate to the project directory:

cd heart-disease-prediction



Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn jupyter



Open the Jupyter Notebook:

jupyter notebook heart.ipynb

Run the cells in the notebook to see the analysis and model training.



# Analysis and Model

* The heart.ipynb notebook contains the complete workflow:

* Exploratory Data Analysis (EDA): Visualizing the relationships between different features and the target variable.

* Data Preprocessing: Handling categorical variables and scaling numerical features.

* Model Building: Training a classification model to predict heart disease.

* Model Evaluation: Assessing the model's performance using metrics like accuracy, precision, and recall.
