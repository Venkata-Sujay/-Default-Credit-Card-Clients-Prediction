# Credit Card Default Prediction System

An end-to-end Machine Learning web application that predicts the likelihood of a customer defaulting on their credit card payments for the next month. 

This project demonstrates a full ML pipeline: from Exploratory Data Analysis (EDA) and model training to deploying a REST API and a user-friendly frontend.

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Model Details](#model-details)

## 🚀 Project Overview

Financial institutions need reliable methods to assess credit risk. This application takes user demographic and financial history data as input and uses a **Random Forest Classifier** to predict whether a customer is High Risk or Low Risk.

**Key Features:**
- **Interactive Web UI:** Clean, dark-themed interface built with vanilla JS and CSS.
- **Real-time Inference:** Python Flask API serves predictions instantly.
- **Probability Estimation:** Displays the actual probability of default (e.g., 78.5%).
- **Reproducible Pipeline:** Scripts included to retrain the model and save artifacts automatically.

## 🛠 Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Dark Theme), JavaScript (Fetch API).
* **Backend:** Python 3, Flask.
* **Machine Learning:** Scikit-learn, Pandas, NumPy, Joblib.
* **Development:** Jupyter Notebook (for EDA).

## wm Project Structure

```text
├── Credit Card Default Prediction.ipynb  # EDA and experimentations
├── default of credit card clients.xls    # Raw Dataset (Excel/CSV)
├── train_model.py                        # Script to process data and train the model
├── test_model.py                         # Script to sanity-check the trained model
├── server.py                             # Flask API to serve predictions
├── model.pkl                             # The saved Random Forest Model (Generated)
├── feature_columns.json                  # Feature metadata (Generated)
├── index.html                            # Frontend HTML (Entry point)
├── styles.css                            # Frontend Styling
└── script.js                             # Frontend Logic
