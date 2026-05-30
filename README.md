# 📈 RAI-Based Financial Time Series Forecasting using LSTM

## 🧠 Project Overview
This project is a Deep Learning-based stock price forecasting system using LSTM (Long Short-Term Memory) neural networks. It predicts future Reliance stock prices based on historical data and demonstrates complete time-series forecasting including preprocessing, training, evaluation, and prediction.

---

## 🚀 Features
- Stock dataset loading and preprocessing
- Date conversion and sorting
- Manual Min-Max scaling demonstration
- Time-series sequence creation
- LSTM deep learning model
- Training and validation loss visualization
- Actual vs predicted price comparison
- Error analysis (MAE, MSE, RMSE)
- Next-day stock price prediction
- Model saving and CSV output generation

---

## 🏗️ Workflow
Stock Data → Preprocessing → Scaling → Sequence Creation → LSTM Training → Prediction → Inverse Scaling → Evaluation → Next Day Prediction → Save Model

---

## 🧠 Model Architecture
- LSTM (50 units, return_sequences=True)
- Dropout (0.2)
- LSTM (50 units)
- Dropout (0.2)
- Dense (25 units, ReLU)
- Dense (1 unit output)

---

## 🛠️ Tech Stack
Python, TensorFlow, Keras, NumPy, Pandas, Matplotlib, Scikit-learn

---
