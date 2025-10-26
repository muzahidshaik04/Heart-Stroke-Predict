
# Heart-Stroke-Predict

## Overview  
Heart-Stroke-Predict is a machine-learning web application that predicts whether an individual is at risk of a heart stroke based on their health and lifestyle data. The project demonstrates the entire workflow from dataset exploration, model building, serialization and deployment in a web-interface.

---

## Features  
- Exploratory data analysis (EDA) of a heart-health dataset.  
- Data preprocessing: feature encoding, scaling, train/test split.  
- Model training: K-Nearest Neighbours (KNN) classifier (as provided).  
- Serialization of the model, scaler and feature columns.  
- Web interface via `app.py` for user input → prediction.  
- Dataset (`heart.csv`) included for reproducibility.

---

## Structure

/ |-- Heart data.ipynb        # Jupyter notebook with EDA, model training |-- heart.csv               # Dataset used for training/testing |-- heart_columns.pkl       # Pickled list of feature column names |-- heart_scaler.pkl        # Pickled scaler object for preprocessing |-- knn_heart_model.pkl     # Serialized trained KNN model |-- app.py                  # Web application for prediction |-- README.md               # This file

---

## Getting Started

### Prerequisites  
- Python 3.7 or higher  
- Required packages (e.g., scikit-learn, pandas, flask)  
  You can install dependencies via:  
  ```bash
  pip install -r requirements.txt

Running the App

1. Clone the repository:

git clone https://github.com/muzahidshaik04/Heart-Stroke-Predict.git
cd Heart-Stroke-Predict


2. Ensure the model files (knn_heart_model.pkl, heart_scaler.pkl, heart_columns.pkl) are present.


3. Run the web application:

python app.py


4. Open your browser and navigate to http://127.0.0.1:5000 (or as specified) and provide user inputs to get a prediction.
