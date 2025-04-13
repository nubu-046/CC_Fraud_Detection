# Credit Card Fraud Detection System

This is a machine learning-based web application built with Streamlit that predicts whether a credit card transaction is fraudulent or legitimate. It uses a pre-trained LightGBM model and supports user-friendly input via a web interface.

---

## Features

- Predicts fraudulent transactions based on transaction details.
- Uses geodesic distance between customer and merchant locations as a feature.
- Automatically encodes categorical data using trained label encoders.
- Lightweight and fast prediction with a LightGBM model.
- Simple and intuitive interface using Streamlit.

---

## Demo

Try the live demo here:  
[https://cc-fraud-detection-system.streamlit.app/](https://cc-fraud-detection-system.streamlit.app/)

---

## Model Details

- Model: LightGBM
- Trained on: Custom dataset with transaction features such as:
  - Merchant name and category
  - Transaction amount
  - Date and time information
  - Customer and merchant geo-locations
  - Credit card number (hashed)
- Categorical columns are label-encoded before prediction.

---

## Requirements

Install the dependencies:

```bash
pip install -r requirements.txt
