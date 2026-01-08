# 🚨Anomaly-Detection-Fraud-Transactions
## 📌 Project Overview

This project implements a **machine learning–based anomaly detection system** to identify **unusual and potentially fraudulent transactions** from transactional data.
The system analyzes transaction behavior, risk indicators, and statistical patterns to flag anomalies that deviate from normal behavior.

This project is highly relevant for **fraud detection, risk monitoring, cybersecurity, and financial analytics** use cases.

## 🎯 Problem Statement

In real-world systems such as banking, e-commerce, and payment platforms, detecting abnormal transactions is critical to prevent fraud and financial loss.
Manual monitoring is inefficient and error-prone.

This project aims to:

* Automatically detect suspicious transactions
* Identify outliers using machine learning
* Provide interpretable results for decision-making

## 🧠 Solution Approach

We use **unsupervised and semi-supervised machine learning techniques** to detect anomalies based on transaction behavior patterns.

### Key Steps:

1. Load and preprocess transactional data
2. Perform exploratory data analysis (EDA)
3. Scale numerical features
4. Apply anomaly detection algorithms
5. Flag and visualize anomalous transactions

## 📊 Dataset Description

The dataset contains transaction-level information with the following features:

| Column Name           | Description                             |
| --------------------- | --------------------------------------- |
| `transaction_id`      | Unique transaction identifier           |
| `amount`              | Transaction amount                      |
| `transaction_hour`    | Hour of transaction (0–23)              |
| `merchant_category`   | Category of merchant                    |
| `foreign_transaction` | Whether transaction is foreign (0/1)    |
| `location_mismatch`   | Location mismatch indicator (0/1)       |
| `device_trust_score`  | Device trust score                      |
| `velocity_last_24h`   | Number of transactions in last 24 hours |
| `cardholder_age`      | Age of cardholder                       |
| `is_fraud`            | Fraud label (used for evaluation only)  |

## 🛠️ Technologies Used

* **Python**
* **Pandas & NumPy**
* **Scikit-learn**
* **Matplotlib & Seaborn**
* **Google Colab**

## 🤖 Machine Learning Techniques Used

* Isolation Forest (Primary model)
* Statistical outlier analysis
* Feature scaling using StandardScaler

## 📈 Key Features of the Project

* Detects anomalies without requiring labeled data
* Handles large transactional datasets efficiently
* Visualizes anomalies for better understanding
* Can be extended to real-time fraud detection systems

## 📊 Output & Visualization

* Flagged anomalous transactions
* Scatter plots highlighting outliers
* Distribution analysis of normal vs anomalous behavior

## 💼 Real-World Use Cases

* Credit card fraud detection
* Banking transaction monitoring
* Cybersecurity threat detection
* Data quality and system monitoring

## 🔍 Results

The model successfully identifies abnormal transaction patterns such as:

* Unusually high transaction amounts
* High transaction velocity
* Foreign transactions with low device trust
* Location mismatches

## 🧩 Future Enhancements

* Add real-time streaming support
* Integrate deep learning–based anomaly detection
* Build a web dashboard using Streamlit
* Deploy as an API for production use
