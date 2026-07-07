# FastAPI Based California House Price Prediction 

# Overview

The project is about house price prediction based on the neighbourhood features in California. A FastAPI application that predicts house prices using a trained Random Forest Regressor.

The trained model ('house_model.joblib') is not included because it exceeds GitHub's 100 MB file size limit.

To regenerate the model:

1. Open 'train.py'
2. Run it
3. 'house_model.joblib' will be created automatically.

# Features

- Single Prediction
- Batch CSV Prediction
- Swagger Documentation
- Pydantic Validation
- Model Health Endpoint

# Tech Stack

Python
FastAPI
Scikit-learn
Pandas
Joblib

# Installation

pip install -r requirements.txt
uvicorn main:app --reload

# API

GET /
GET /health
POST /predict
POST /predict-file

## Dataset

California Housing Dataset
