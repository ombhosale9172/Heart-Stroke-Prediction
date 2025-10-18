# Heart Disease Prediction App

A Streamlit web application for predicting heart disease risk using machine learning.

## Features

- Interactive web interface built with Streamlit
- Uses KNN model for predictions
- Handles various input parameters including:
  - Age
  - Sex
  - Chest Pain Type
  - Resting Blood Pressure
  - Cholesterol
  - Fasting Blood Sugar
  - Resting ECG
  - Maximum Heart Rate
  - Exercise-Induced Angina
  - ST Depression
  - ST Slope

## Setup

1. Clone the repository
```bash
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the app
```bash
streamlit run app.py
```

## Project Structure

- `app.py` - Main Streamlit application
- `KNN_heart.pkl` - Trained KNN model
- `scaler.pkl` - Feature scaler
- `columns.pkl` - Expected column names

## Model Details

The application uses a K-Nearest Neighbors (KNN) classifier trained on heart disease data. Features are scaled using StandardScaler to ensure optimal model performance.

## Requirements

- Python 3.8+
- Streamlit
- scikit-learn
- pandas
- joblib