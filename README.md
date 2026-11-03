# ❤️ Heart Disease Prediction

A machine learning web app that predicts the risk of heart disease from 11 health inputs. Built with Python, Scikit-learn and Streamlit.

🔗 **Live App:** https://heart-disease-prediction-pyjdcjjcbpduqkrkcuwxap.streamlit.app/

## Overview
The user enters details such as age, cholesterol, blood pressure, ECG result and chest pain type. A KNN model then predicts whether the risk of heart disease is high or low.

## Dataset
Heart Failure Prediction dataset (`heart.csv`) with 11 features and the target `HeartDisease` (1 = risk, 0 = normal).

| Type | Features |
| Numerical | Age, RestingBP, Cholesterol, MaxHR, Oldpeak |
| Categorical | Sex, ChestPainType, FastingBS, RestingECG, ExerciseAngina, ST_Slope |

## Approach
1. Explored the data in `heartdisease.ipynb`
2. One-hot encoded the categorical features
3. Scaled the features
4. Trained a K-Nearest Neighbors (KNN) classifier
5. Saved the model, scaler and column list with joblib
6. Built a Streamlit app and deployed it on Streamlit Community Cloud

## Project Structure
- `app.py`: Streamlit app
- `heartdisease.ipynb`: model training notebook
- `heart.csv`: dataset
- `KNN_heart_model.pkl`: trained model
- `heart_scaler.pkl`: fitted scaler
- `heart_columns.pkl`: expected feature columns
- `requirements.txt`: dependencies

## Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Tech Stack
Python, Pandas, Data visualization, Matplotlib and Seaborn, Scikit-learn, Joblib, Streamlit

## Disclaimer
This project is for educational purposes only and is not a substitute for medical advice.

## Author
Dinesh Vishwakarma | [LinkedIn](https://www.linkedin.com/in/dinesh-vishwakarma-69b9b6310/)
