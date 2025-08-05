# 🟡 Gold-Price-Prediction-Vs-USD
<img width="822" height="538" alt="image" src="https://github.com/user-attachments/assets/691829fb-5c26-4627-92ee-cadd84991172" />

This project aims to forecast gold prices in Egypt by analyzing their relationship with the USD and global market prices using traditional ML models and time series forecasting.

---

## 📌 Introduction

Gold holds great significance in Egypt, both culturally and economically. From ancient times to the modern era, gold has symbolized wealth, heritage, and financial security. As Egypt's economy evolved, the local gold market started reflecting global economic trends and USD fluctuations. This project investigates these relationships to predict gold prices effectively.

---

## 🎯 Project Goal

- Analyze the correlation between gold prices in Egypt and the US dollar
- Forecast gold prices using:
  - ARIMA (time-series model)
  - ML models: SVR, XGBoost, Bayesian Ridge, Gradient Boosting, Decision Tree, Random Forest
  - (Upcoming) Deep learning: LSTM & RNN
- Predict prices for various gold karats (24K, 22K, 21K, 18K, 14K, 12K)

---

## 📊 Dataset Features

| Feature                     | Description |
|----------------------------|-------------|
| Date                       | Observation date |
| USD Price                  | Dollar price |
| 24K - Local Price/Sell     | 24K gram sell price (Egypt) |
| 24K - Local Price/Buy      | 24K gram buy price (Egypt) |
| ...                        | ... and other karats |
| 24K - Global Price         | 24K gram global price |
| ...                        | Global prices for other karats |

---

## 📈 Models & Evaluation

| Model            | MAE     | MSE      | RMSE     | R²      | MAPE    |
|------------------|---------|----------|----------|---------|---------|
| ARIMA            | —       | —        | 6.48     | —       | —       |
| SVR              | 28.50   | 1653.56  | 40.66    | 0.948   | 0.0176  |
| XGBoost          | 34.54   | 2908.35  | 53.93    | 0.930   | 0.0184  |
| Bayesian Ridge   | 28.52   | 1655.79  | 40.69    | 0.948   | 0.0175  |
| Gradient Boosting| 27.68   | 1709.55  | 41.34    | 0.946   | 0.0169  |
| Decision Tree    | 31.00   | 1981.91  | 44.51    | 0.937   | 0.0190  |
| 🥇 Random Forest | 27.60   | 1516.32  | 38.94    | 0.952   | 0.0168  |

➡️ **Conclusion**: Random Forest had the best accuracy among all ML models with ~96%.

---

## 🔮 Upcoming Work

- Implement LSTM and RNN for deeper temporal analysis
- Expand predictions to all karats of gold
- Build a dashboard for real-time visualization

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 Kaggle Notebook

[Gold Price Prediction](https://www.kaggle.com/code/fatmayousufmohamed/gold-prices/notebook#notebook-container)

