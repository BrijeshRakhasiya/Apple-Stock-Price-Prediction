# 📈 Apple Stock Price Prediction 

This project uses **AutoTS**, an automated time series forecasting library, to predict the next 5 days of **Apple Inc. (AAPL)** stock prices. The historical stock data is fetched from Yahoo Finance, and interactive visualizations are created using Plotly for insightful analysis.

---

## 📂 Project Overview

- **Goal:** Predict Apple stock prices for the next 5 trading days from the latest historical data (up to July 10, 2025).
- **Data Source:** [Yahoo Finance](https://finance.yahoo.com/quote/AAPL/)
- **Time Frame:** July 10, 2024 – July 10, 2025
- **Forecasting Tool:** [AutoTS](https://github.com/winedarksea/AutoTS)

---

## 🛠️ Tools & Libraries

- `yfinance` – historical stock data fetching
- `pandas` – data wrangling
- `AutoTS` – automated time series forecasting
- `plotly` – interactive plotting and visualization
- `sklearn`, `matplotlib` – additional utilities

---

## 📊 Predicted Prices (Next 5 Days)

| Date       | Predicted Price (USD) |
|------------|------------------------|
| 2025-07-10 | 214.08                 |
| 2025-07-11 | 213.40                 |
| 2025-07-14 | 213.40                 |
| 2025-07-15 | 212.87                 |
| 2025-07-16 | 211.96                 |

---

## 📈 Workflow

1. **Data Collection**
   - Retrieved 1-year stock price data (`Open`, `High`, `Low`, `Close`, `Volume`) using `yfinance`.

2. **Preprocessing**
   - Cleaned and formatted the time series to match AutoTS requirements.

3. **Forecasting with AutoTS**
   - Trained an ensemble of models using AutoTS.
   - Automatically selected the best-performing model.
   - Forecasted the next 5 days of closing prices.

4. **Visualization**
   - Used **Plotly** for dynamic line plots to visualize historical and predicted prices.

---

**Install Dependencies**
```
pip install yfinance autots plotly pandas

```
**Run the Notebook**
```
jupyter notebook "Apple Stock Price Prediction.ipynb"
```


## 📄 License

This project is licensed under the MIT License.

---
**Made ❤️ by Brijesh Rakhasiya**




