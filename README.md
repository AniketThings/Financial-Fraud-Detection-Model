# Financial Fraud Detection Using PaySim Dataset

This project demonstrates a machine learning approach to detect financial fraud using the synthetic PaySim dataset. PaySim simulates mobile money transactions and contains labels indicating whether a transaction is fraudulent or not. The project uses Python and several popular libraries to preprocess data, train a classification model, and evaluate its performance.

---

Here is the Direct link to the dashborad
https://dynamic-platypus-cca973.netlify.app/

## Dataset

The dataset used for this project is the **PaySim1** dataset from Kaggle:

- [PaySim1 Dataset on Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1)

This dataset simulates realistic mobile money transactions, providing a rich base for building fraud detection models.

---

## Features

- **Type**: The type of transaction (e.g., CASH_IN, CASH_OUT, etc.).
- **Amount**: The amount of the transaction.
- **Old Balance & New Balance** for both sender (origin) and receiver (destination).
- **Fraud Labels**: Binary label indicating whether a transaction is fraudulent.

---

## Project Highlights

- Data loading and preprocessing including one-hot encoding of categorical variables.
- Handling skewed numerical features by applying log transformation.
- Splitting data into training and testing sets with stratification.
- Feature scaling using MinMaxScaler.
- Training an XGBoost classification model.
- Model evaluation through accuracy, F1 score, ROC AUC score, and confusion matrix visualization.

---

## Dependencies / Required Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

### Installation

You can install the required libraries via pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
