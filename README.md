# Customer Churn Prediction

Customer Churn Prediction using Machine Learning.

## Project Overview

This project predicts whether a customer is likely to churn using machine learning techniques. The project uses a telecom customer dataset and performs data preprocessing, exploratory data analysis, feature encoding, model training, and evaluation.

## Dataset

- Total records: 7043
- Total features: 21
- Target variable: Churn
- Dataset contains customer information such as tenure, monthly charges, contract type, internet service, payment method, and other services.

## Data Preprocessing

The following preprocessing steps were performed:

- Converted `TotalCharges` into numeric format.
- Handled 11 missing values in `TotalCharges` using the median.
- Removed `customerID` as it is not useful for prediction.
- Converted categorical variables into numerical features using one-hot encoding.
- Split the dataset into 80% training and 20% testing data.

## Machine Learning Models

Two classification models were trained:

1. Logistic Regression
2. Random Forest Classifier

## Model Results

| Model | Accuracy | ROC-AUC |
|---|---:|---:|
| Logistic Regression | 80.62% | 0.8423 |
| Random Forest | 79.35% | 0.8279 |

## Evaluation

The models were evaluated using:

- Accuracy
- Classification Report
- ROC-AUC
- Confusion Matrix
- ROC Curve

## Conclusion

The project demonstrates how machine learning can be used to predict customer churn. Logistic Regression achieved an accuracy of 80.62% and a ROC-AUC score of 0.8423 on the test dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## Project File

The complete implementation is available in:

`Customer_Churn_Prediction.ipynb`

## Reference

This project was developed using a publicly available customer churn project as a reference and adapted for learning and internship purposes.
