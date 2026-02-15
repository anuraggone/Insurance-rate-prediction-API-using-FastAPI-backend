# Insurance Premium Prediction API

A FastAPI based REST API that predicts insurance premium categories using a Machine Learning model integrated into the backend.

This project demonstrates:
- Training and developing Machine Learning model using Random Forest Classifier algorithm
- FastAPI backend development
- Pydantic request validation
- Feature engineering inside the API
- Integration of a ML model with the Backend 

---

## Overview

The API accepts various user Input, validates it using Pydantic, performs feature engineering, and returns a predicted insurance premium category:

- Low
- Medium
- High

The ML model was trained separately and saved as `insurance_model.pkl`, then integrated into the FastAPI application.

---

## Tech Stack

- FastAPI
- Pydantic
- scikit-learn (Random Forest Classifier)
- Uvicorn
- Pickle 

---

## Project Structure
├── main.py
├── insurance_model.pkl
├── requirements.txt
└── README.md

