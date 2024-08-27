# Heart Disease Prediction

This project aims to predict the likelihood of heart disease in patients using a machine learning model trained on a dataset of patient health metrics.

## Project Overview

This project involves the following steps:
1. **Data Collection and Processing**: Load and preprocess the heart disease dataset.
2. **Model Training**: Train a logistic regression model to predict the presence of heart disease.
3. **Model Evaluation**: Evaluate the accuracy of the trained model.

## Dataset

The dataset used for this project contains the following features:
- `age`: Age of the patient.
- `sex`: Sex of the patient (1 = male, 0 = female).
- `cp`: Chest pain type (0-3).
- `trestbps`: Resting blood pressure (in mm Hg).
- `chol`: Serum cholesterol (in mg/dl).
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false).
- `restecg`: Resting electrocardiographic results (0-2).
- `thalach`: Maximum heart rate achieved.
- `exang`: Exercise-induced angina (1 = yes, 0 = no).
- `oldpeak`: ST depression induced by exercise relative to rest.
- `slope`: The slope of the peak exercise ST segment (0-2).
- `ca`: Number of major vessels (0-3) colored by fluoroscopy.
- `thal`: Thalassemia (0 = normal, 1 = fixed defect, 2 = reversible defect).
- `target`: Target variable indicating the presence of heart disease (1 = presence, 0 = absence).

## Installation

To run the project, you need to install the following dependencies:

```bash
pip install numpy pandas scikit-learn
