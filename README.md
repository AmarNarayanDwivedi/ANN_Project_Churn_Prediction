# Churn Prediction Using Artificial Neural Networks (ANN)

## Overview

This project uses Artificial Neural Networks (ANN) to predict customer churn based on a dataset containing customer attributes. The goal is to create a predictive model that identifies whether a customer will leave the company (churn) or remain a customer. By identifying at-risk customers, businesses can take proactive steps to retain them.

The model is built using Keras and TensorFlow libraries, and it is trained on a customer dataset with several features, including demographic information, services subscribed to, and usage patterns.

---

## Project Structure

```bash
ANN_Project_Churn_Prediction/

│── Churn_Modelling.csv           # Customer data CSV file
│── model.h5                      # Trained model saved in HDF5 format
│── experiments.ipynb             # Jupyter notebook with analysis and model training
│── app.py                        # Code for Streamlit Application
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```
# Churn Prediction Using Artificial Neural Networks (ANN)

## Features of the Project

### 1. Data Preprocessing:
   - Clean and transform the raw customer data for model training.
   - Handle missing values, categorical variables, and scale numerical features.

### 2. Model Training:
   - A neural network model is created using Keras and TensorFlow.
   - The model is trained using customer features to predict churn.
   - Hyperparameter tuning and evaluation of different architectures.

### 3. Model Evaluation:
   - Evaluate the model's performance using metrics like accuracy, precision, recall, and F1-score.
   - Confusion matrix and ROC curve visualizations.

### 4. Churn Prediction:
   - Predict whether a given customer will churn based on their attributes.

---

## Requirements

To run this project, you'll need Python 3.6 or higher. Install the necessary dependencies using the provided `requirements.txt`.

```bash
pip install -r requirements.txt
```
### Dependencies include:

- **tensorflow**: Deep learning framework used for building the ANN model.
- **pandas**: For data manipulation and cleaning.
- **numpy**: For numerical operations.
- **scikit-learn**: For data preprocessing and evaluation.
- **matplotlib** and **seaborn**: For visualizations.

## Installation

1. **Clone the repository:**
```bash
git clone https://github.com/AmarNarayanDwivedi/ANN_Project_Churn_Prediction.git
```

2. **Navigate to the project directory:**
```bash
cd ANN_Project_Churn_Prediction
```

3. **Install dependencies:**
```bash
pip install -r requirements.txt
```



