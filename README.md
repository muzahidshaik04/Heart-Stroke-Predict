
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
### Tech Stack
- Python 3.8+
- Flask
- Scikit-learn
- Pandas
- Numpy
    

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

python app.py http://localhost:8502/

