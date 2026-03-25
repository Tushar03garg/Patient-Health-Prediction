# Patient Health Prediction using Machine Learning

## Project Overview

This project focuses on predicting whether a patient is **Healthy** or **Unhealthy** using supervised machine learning classification techniques. The model is trained on a healthcare dataset containing medical, lifestyle, and physiological indicators such as Age, BMI, Blood Pressure, Cholesterol, Glucose Level, Sleep Hours, Exercise Hours, Stress Level, and Medical History.

The goal of this project is to support early risk identification and assist healthcare researchers in making informed decisions based on patient health data.

---

## Problem Statement

Healthcare institutions often need to identify individuals who may be at higher health risk based on their medical and lifestyle data. This project builds machine learning models to classify patient health status using predictive analytics.

---

## Dataset Description

The dataset contains health-related features collected from patient records. Each record represents one individual.

### Key Features

* Age
* BMI (Body Mass Index)
* Blood Pressure
* Cholesterol
* Glucose Level
* Heart Rate
* Sleep Hours
* Exercise Hours
* Stress Level
* Smoking
* Alcohol Consumption
* Medical History
* Physical Activity
* Diet Type
* Target (Healthy / Unhealthy)

---

## Machine Learning Models Used

The following classification algorithms were implemented:

1. Logistic Regression
2. Support Vector Machine (SVM Classifier)
3. Decision Tree Classifier
4. Voting Classifier (Heterogeneous Ensemble Method)

The Voting Classifier combines predictions from multiple models to improve overall performance and model stability.

---

## Ensemble Technique

A **Heterogeneous Ensemble Learning** method was used through the Voting Classifier.

Models combined:

* Logistic Regression
* Support Vector Machine
* Decision Tree

This approach improves prediction accuracy by aggregating outputs from different algorithms.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn (sklearn)
* Jupyter Notebook

---

## Model Evaluation Metrics

The performance of each model was evaluated using classification metrics:

* Accuracy Score
* Precision Score
* Recall Score

These metrics help measure the effectiveness of the model in predicting patient health status.

---

## Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Model Training
6. Model Evaluation
7. Ensemble Modeling using Voting Classifier
8. Prediction

---

## How to Run the Project

Step 1:

Clone the repository

git clone https://github.com/your-username/your-repository-name.git

Step 2:

Install required libraries

pip install -r requirements.txt

Step 3:

Run the notebook

jupyter notebook

Open:

NovaGen.ipynb

---

## Project Structure

project-folder/

│── NovaGen.ipynb
│── novagen_dataset.csv
│── README.md
│── requirements.txt

---

## Future Improvements

* Hyperparameter tuning
* Feature engineering
* Cross-validation
* Model deployment using Flask or Streamlit
* Use advanced ensemble methods like Random Forest or XGBoost

---

## Author

Tushar Garg

GitHub: https://github.com/Tushar03garg
