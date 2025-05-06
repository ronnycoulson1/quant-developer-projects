# Moving Average Crossover Strategy

This project implements a basic moving average crossover trading strategy using Python. It simulates buying when the short-term moving average crosses above the long-term moving average, and selling when it crosses below.

---

## ⚙️ How It Works

1. **Load historical data** using `yfinance`.
2. **Define strategy** using short and long moving averages.
3. **Run backtest** to simulate trades.
4. **Evaluate metrics** such as total return, win rate, and Sharpe ratio.
5. **Plot results** including price chart and trade signals.

---

## 📂 Project Structure

- `data_loader.py`: Loads and preprocesses stock data
- `strategy.py`: Contains crossover logic
- `backtest.py`: Executes the trading simulation
- `metrics.py`: Calculates performance statistics
- `main.py`: Entry point to run the full pipeline
- `requirements.txt`: Package dependencies

---

## ▶️ Running the Project

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
