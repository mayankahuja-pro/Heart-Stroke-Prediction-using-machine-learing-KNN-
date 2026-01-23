# Heart Stroke Prediction using KNN

This is a Streamlit web application that predicts the risk of heart disease/stroke using a K-Nearest Neighbors (KNN) machine learning model.

## Features
- Interactive UI using Streamlit sliders and dropdowns.
- Real-time prediction based on clinical parameters.
- Built-in data preprocessing (scaling and one-hot encoding).

## Clinical Parameters Used for Prediction
- **Age**: Age of the patient.
- **Sex**: Male (M) or Female (F).
- **Chest Pain Type**: ATA, NAP, TA, or ASY.
- **Resting Blood Pressure**: mm Hg.
- **Cholesterol**: mg/dL.
- **Fasting Blood Sugar**: > 120 mg/dL (1 = True, 0 = False).
- **Resting ECG**: Normal, ST, or LVH.
- **Max Heart Rate**: Beats per minute.
- **Exercise-Induced Angina**: Yes (Y) or No (N).
- **Oldpeak**: ST depression.
- **ST Slope**: Up, Flat, or Down.

## How to Run Locally
1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd Heart-Stroke-Prediction-using-machine-learing-KNN--main
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Files in this Repository
- `app.py`: Main Streamlit application.
- `heart.csv`: Dataset used for training.
- `KNN_heart.pkl`: Trained KNN model.
- `scaler.pkl`: Scaler used for feature normalization.
- `columns.pkl`: List of expected columns for the model.
- `requirements.txt`: Python package dependencies.

## Deployment
This app is ready to be deployed on **Streamlit Cloud**. Make sure all `.pkl` files are uploaded to your GitHub repository for the app to function correctly.
