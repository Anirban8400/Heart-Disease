# Heart Disease Prediction Model

This project focuses on building a machine learning model to predict the likelihood of heart disease based on a dataset from Kaggle. Various classification algorithms such as Random Forest, Gradient Boosting, Logistic Regression, and K-Nearest Neighbors (KNN) were employed to predict whether a patient is at risk of heart disease or not.

## Project Overview

The goal of this project was to develop an accurate model that can predict heart disease risk based on various input features, such as age, sex, cholesterol levels, blood pressure, and other health-related metrics.

### Key Algorithms Used:
- **Random Forest**
- **Gradient Boosting**
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**

## Dataset

The dataset used for this project is from Kaggle and contains the following columns:

- `age`: Age of the patient
- `sex`: Gender of the patient
- `cp`: Chest pain type
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol
- `fbs`: Fasting blood sugar
- `restecg`: Resting electrocardiographic results
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise induced angina
- `oldpeak`: Depression induced by exercise relative to rest
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy
- `thal`: Thalassemia

## Installation

To run the project, clone the repository and install the necessary dependencies.

1. Clone the repository:
 git clone https://github.com/your-username/heart-disease-prediction.git

2. Navigate to the project directory:

 
3. Create and activate a virtual environment (optional):
python3 -m venv venv source venv/bin/activate # On Windows use venv\Scripts\activate

4. Install required packages:

## Usage

1. Load the dataset and preprocess the data.
2. Train and evaluate models such as Random Forest, Gradient Boosting, Logistic Regression, and K-Nearest Neighbors (KNN).
3. Compare the performance of the models using metrics like accuracy, precision, recall.
4. Visualize the results and choose the best-performing model for heart disease prediction.

## Results
The Random Forest model achieved the highest accuracy, followed by Gradient Boosting and Logistic Regression.
The KNN model, while accurate, performed slightly worse due to sensitivity to feature scaling.
The models were evaluated using accuracy, precision, recall, and ROC-AUC score.

