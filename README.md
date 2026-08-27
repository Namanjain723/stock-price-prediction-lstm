<div align="center">

# 📈 Stock Price Prediction with LSTM

### Forecasting Netflix (NFLX) closing prices using a deep-learning time-series model.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</div>

---

## 📌 Overview

This project predicts **Netflix (NFLX) stock closing prices** from historical market data
using an **LSTM (Long Short-Term Memory)** neural network — a recurrent architecture built
for sequential, time-dependent data.

## 🗂️ Data
`NFLX.csv` — historical Netflix OHLC price history (Open, High, Low, Close, Volume).

## 🔬 Approach
1. **Explore** the price history with Matplotlib / Seaborn to understand trend and volatility.
2. **Pre-process** — scale closing prices with `MinMaxScaler` and build rolling look-back sequences.
3. **Model** — a Keras `Sequential` network with stacked **LSTM** + `Dense` layers.
4. **Train & evaluate** — fit on the training window, predict on unseen data, and **plot predicted vs actual** prices.

## 💡 Outcome
A working deep-learning pipeline that captures temporal patterns in stock prices and visualises how closely the model tracks real market movement.

## 🧰 Tech stack
**Python · TensorFlow / Keras (LSTM) · scikit-learn · Pandas · NumPy · Matplotlib · Seaborn · Jupyter**

## ▶️ Run
```bash
git clone https://github.com/Namanjain723/Stock-prediction-.git
pip install tensorflow scikit-learn pandas numpy matplotlib seaborn tqdm jupyter
jupyter notebook "STOCK PREDICTION (TASK-2).ipynb"
```

> ⚠️ Educational project — not financial advice.

---

## 👤 Author
**Naman Jain** — Data Analyst & AI Developer
🌐 [Portfolio](https://pixlforgestudio.in/) · ✉️ info@pixlforgestudio.in · 🐙 [@Namanjain723](https://github.com/Namanjain723)
