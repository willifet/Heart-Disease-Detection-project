# Heart Disease Detection Project

### Overview 

Heart disease is one of the leading causes of death worldwide. Early detection of heart disease can significantly improve treatment outcomes and patient care. This project aims to build a machine learning model using Python and Scikit-Learn to predict whether a patient has heart disease based on clinical data.

### Dataset Details 

We use the Heart Disease UCI dataset, which contains various health indicators such as age, cholesterol levels, blood pressure, and more.

Total Samples: 1024 patients

Features: 13 clinical attributes (e.g., age, sex, cholesterol, blood pressure, etc.)

Target Variable: Presence (1) or absence (0) of heart disease

Format: CSV file

## Installation

### Prerequisites

Ensure you have Python 3.7+ installed, along with the following dependencies:

pip install numpy pandas scikit-learn matplotlib seaborn

## Model Architecture

We experiment with various machine learning models, including:

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Feature selection and hyperparameter tuning are applied to optimize performance.

### Training the Model

Run the following command to train the model:

python src/train.py

### Evaluating the Model
To test the trained model on the test dataset:

python src/test.py

### Making Prediction

To make predictions on new patient data:

python src/predict.py --input path/to/patient_data.csv

### Result

The best-performing model achieves an accuracy of approximately 85-90%, depending on feature selection and hyperparameter tuning.

### Future Improvement

Test with deep learning models (e.g., neural networks).

Integrate real-time patient data for continuous monitoring.

Deploy as a web application using Flask or FastAPI.

Use SHAP (SHapley Additive Explanations) for better model interpretability.
