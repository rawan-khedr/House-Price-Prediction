# House Price Prediction

## Project Overview

This project is an end-to-end Machine Learning application that predicts house prices based on property features. The project covers the complete machine learning workflow, including data exploration, preprocessing, model training, evaluation, model deployment, and API development using FastAPI.

## Features

- Data exploration and visualization (EDA)
- Data cleaning and feature engineering
- Multiple regression models
- Model comparison using evaluation metrics
- Export trained model using Joblib
- FastAPI backend for predictions
- Ready for frontend integration

---

## Dataset

The dataset contains house listings with information such as:

- Location
- Carpet Area
- Super Area
- Number of Bathrooms
- Balcony
- Floor
- Furnishing Status
- Ownership
- Transaction Type
- House Price

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- FastAPI
- Uvicorn

---

## Machine Learning Models

The following regression models were trained and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

Models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Project Structure

```
House-Price-Prediction/
│
├── data/
│   └── house_prices.csv
│
├── notebooks/
│   └── ITI_Project.ipynb
│
├── backend/
│   ├── app.py
│   ├── house_price.pkl
│   ├── locations.json
│   └── requirements.txt
│
├── README.md
│
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/rawan-khedr/House-Price-Prediction.git
```

Navigate to the project folder:

```bash
cd House-Price-Prediction
```

Install the required packages:

```bash
pip install -r backend/requirements.txt
```

---

## Running the API

Navigate to the backend folder:

```bash
cd backend
```

Run the FastAPI application:

```bash
uvicorn app:app --reload
```

The API will be available at:

```
http://127.0.0.1:8000
```

Interactive API documentation:

```
http://127.0.0.1:8000/docs
```

---

## Model Export

The trained model is saved as:

```
house_price.pkl
```

The available property locations are saved as:

```
locations.json
```

These files are loaded automatically by the FastAPI backend for making predictions.

---

## Workflow

1. Load the dataset
2. Perform Exploratory Data Analysis (EDA)
3. Clean and preprocess the data
4. Engineer relevant features
5. Train multiple regression models
6. Evaluate model performance
7. Save the best model
8. Build a FastAPI backend
9. Serve predictions through an API

---

## Future Improvements

- React frontend
- Docker deployment
- Cloud deployment (Azure / AWS)
- Hyperparameter tuning
- Cross-validation
- XGBoost implementation

---

## Author

Rawan Khedr

ITI Machine Learning Project
