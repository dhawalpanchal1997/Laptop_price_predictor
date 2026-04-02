# Laptop Price Predictor 💻💰

## Project Overview
This is a **Machine Learning** web application that predicts the price of a laptop based on its configuration (Brand, RAM, GPU, OS, Weight, etc.). The project involves a complete end-to-end pipeline from data cleaning and Exploratory Data Analysis (EDA) to model deployment using **Streamlit**.

## Features
* **Price Prediction:** Get instant price estimates based on hardware specifications.
* **Interactive UI:** A clean, user-friendly interface built with Streamlit.
* **ML Pipeline:** Includes a pre-processed data pipeline (`pipe.pkl`) for consistent transformations and predictions.

## Tech Stack
* **Language:** Python
* **Analysis & Modeling:** Jupyter Notebook, Pandas, NumPy, Scikit-Learn
* **Web Framework:** Streamlit (via `app.py`)
* **Deployment:** Pickle for model serialization

## Project Structure
```text
├── laptop_data.csv            # Raw dataset
├── laptop_price_predictor.ipynb # Data Analysis & Model Training
├── app.py                     # Streamlit web application
├── df.pkl                     # Processed dataframe
├── pipe.pkl                   # Trained ML Pipeline
├── requirements.txt           # Project dependencies
└── .gitignore                 # Files to ignore in git
