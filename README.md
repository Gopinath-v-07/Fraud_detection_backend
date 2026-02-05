# Fraud_detection_backend
This repository contains the Machine Learning backend for a Fraud Detection System.
The backend exposes a REST API that predicts whether a financial transaction is Fraudulent or Normal using an anomaly detection model.

📌 Project Overview

Fraud detection is a critical problem in banking and digital payments due to:
Highly imbalanced datasets
Rare but costly fraud events
Need for real-time predictions
This project focuses on building a production-ready ML backend, not just a notebook-based solution.

🧠 Machine Learning Approach
Model Used: Isolation Forest (Anomaly Detection)

Why Isolation Forest?

Works well with imbalanced data
Detects outliers without needing labeled fraud-heavy datasets
Preprocessing: StandardScaler for feature normalization
(Autoencoder-based anomaly detection planned as a future upgrade)

 Tech Stack
🔹 Backend

Python
FastAPI
Uvicorn

🔹 Machine Learning

Scikit-learn
NumPy
Joblib

🔹 Tools

Google Colab (model training)
Local system (API deployment)
GitHub (version control)
