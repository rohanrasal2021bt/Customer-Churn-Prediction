# Customer Churn Prediction using Machine Learning

## Overview

This project predicts whether a telecom customer is likely to churn using Machine Learning techniques.

The complete pipeline includes:

- Data preprocessing
- Handling categorical variables
- Class imbalance handling using SMOTE
- Training multiple ML models
- Model evaluation
- Saving the trained model and encoders for deployment

---

## Dataset

Dataset used:

**Telco Customer Churn Dataset**

Features include:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Internet Service
- Contract Type
- Monthly Charges
- Total Charges
- Payment Method
- Churn (Target Variable)

---

## Project Workflow

1. Load Dataset
2. Data Cleaning
3. Handle Missing Values
4. Encode Categorical Variables
5. Balance Dataset using SMOTE
6. Train Machine Learning Models
7. Compare Performance
8. Save Best Model
9. Save Encoders

---

## Machine Learning Algorithms Used

- Decision Tree
- Random Forest
- XGBoost

---

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn
- Pickle

---

## Model Evaluation

Evaluation metrics include:

- Accuracy
- Confusion Matrix
- Classification Report
- Cross Validation Score

---

## Saved Files

```
customer_churn_model.pkl
```

Contains the trained ML model.

```
encoders.pkl
```

Contains Label Encoders used during preprocessing.

---

## Repository Structure

```
Customer-Churn-Prediction/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── models/
│   ├── customer_churn_model.pkl
│   └── encoders.pkl
│
├── notebooks/
│   └── Customer_Churn_Prediction_using_ML.ipynb
│
├── README.md
├── requirements.txt
├── .gitignore
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction.git
```

Move into the project

```bash
cd Customer-Churn-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## Future Improvements

- Streamlit Web App
- Hyperparameter Tuning
- Feature Importance Visualization
- Model Deployment using Flask/FastAPI
- Docker Support

---

## Author

**Rohan Adhik Rasal**

M.Tech Computational Biology  
IIIT Delhi