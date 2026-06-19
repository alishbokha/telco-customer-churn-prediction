# telco-customer-churn-prediction
Customer churn prediction using machine learning techniques including Logistic Regression and Random Forest on the Telco Customer Churn dataset.
# Customer Churn Prediction

## Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. This project uses Machine Learning techniques to predict whether a customer is likely to leave a telecom company based on their service usage and account information.

The project analyzes customer behavior and builds predictive models to identify customers at risk of churning.

---

## Dataset

Dataset: Telco Customer Churn Dataset

The dataset contains information such as:

- Gender
- Senior Citizen Status
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming Services
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn Status

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns
- Handled missing values
- Encoded categorical features using One-Hot Encoding
- Scaled numerical features using MinMaxScaler
- Split data into training and testing datasets

---

## Machine Learning Models

### 1. Random Forest Classifier

Random Forest was trained to identify important factors contributing to customer churn.

### 2. Logistic Regression

Logistic Regression was used as the final prediction model and achieved the best performance.

---

## Results

| Model | Accuracy |
|---------|---------|
| Random Forest | 78.70% |
| Logistic Regression | 80.25% |

### Classification Report (Logistic Regression)

- Accuracy: 80.25%
- Precision (Churn): 66%
- Recall (Churn): 52%
- F1-Score (Churn): 58%

---

## Important Features

The most influential factors affecting customer churn were:

- Total Charges
- Tenure
- Monthly Charges
- Payment Method
- Internet Service Type
- Contract Type
- Paperless Billing

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Transformation
6. Model Training
7. Model Evaluation
8. Customer Churn Prediction

---

## Future Improvements

- Hyperparameter tuning
- XGBoost implementation
- Deep Learning models
- Deployment using Flask or Streamlit
- Real-time prediction dashboard

---



---

## How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Open the Jupyter Notebook:

```bash
jupyter notebook project_customer_churn.ipynb
```

Run all cells to reproduce the results.
