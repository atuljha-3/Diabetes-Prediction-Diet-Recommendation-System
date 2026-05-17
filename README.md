# Diabetes Prediction & Diet Recommendation System

**Predict. Prevent. Personalize — a machine learning system for diabetes risk prediction and smart diet recommendation.**

This project is a complete Diabetes Prediction and Diet Recommendation System that uses machine learning to estimate a patient's diabetes risk based on clinical health measurements such as glucose level, BMI, blood pressure, insulin, age, and diabetes pedigree function.

The system not only predicts whether a patient is at low, moderate, or high diabetes risk, but also provides personalized diet recommendations, meal plans, dietary guidelines, and foods to avoid. It includes an interactive GUI where users can enter patient data, view diabetes probability, identify risk factors, and receive health-focused diet suggestions.

The machine learning pipeline includes data preprocessing, missing-value handling, feature engineering, model training, evaluation, and visualization. The project also compares multiple models and uses performance metrics such as accuracy, F1-score, and ROC-AUC to evaluate prediction quality.

## Key Features

- Diabetes risk prediction using machine learning
- Personalized diet recommendation based on risk level
- Interactive GUI built with Tkinter
- Patient input form with quick-fill and random patient options
- Risk probability gauge and visual result display
- Meal plans for low, moderate, and high-risk patients
- Foods to avoid and dietary guideline suggestions
- Data preprocessing and missing-value treatment
- Feature engineering using clinically inspired features
- Model evaluation with accuracy, F1-score, and ROC-AUC
- Visualizations for dataset distribution, outcomes, ROC curves, and feature importance

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Tkinter
- Pillow
- XGBoost optional
- SMOTE optional

## Project Overview

The project contains two main parts:

1. **Machine Learning Backend**  
   Handles dataset loading, preprocessing, feature engineering, model training, evaluation, and patient-level prediction.

2. **Graphical User Interface**  
   Provides a user-friendly desktop interface where users can enter patient details, generate predictions, and view personalized diet recommendations.

## Disclaimer

This project is created for educational and academic purposes only. The prediction result is a screening output and should not be considered a medical diagnosis. Always consult a qualified healthcare professional for medical advice.
