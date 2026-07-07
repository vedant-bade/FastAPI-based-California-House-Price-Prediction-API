# FastAPI Based California House Price Prediction 

# Overview

The project is about house price prediction based on the neighbourhood features in California. A FastAPI application that predicts house prices using a trained Random Forest Regressor.

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