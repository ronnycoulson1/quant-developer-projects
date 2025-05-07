# 📈 Moving Average Crossover Strategy

This project implements a simple moving average crossover trading strategy using historical stock price data. The strategy generates buy/sell signals when a short-term moving average crosses a long-term moving average.

---

## ⚙️ How It Works

1. **Load historical stock data** using `yfinance`.
2. **Calculate moving averages** (short and long).
3. **Generate trading signals** based on crossover events.
4. **Backtest the strategy** over the given period.
5. **Evaluate performance** using metrics like total return and Sharpe ratio.
6. **Visualize results** (e.g., price chart + signals).

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `main.py` | Entry point — runs the entire strategy pipeline |
| `data_loader.py` | Downloads historical data using `yfinance` |
| `strategy.py` | Defines the crossover signal generation logic |
| `backtest.py` | Simulates trades and computes portfolio values |
| `metrics.py` | Evaluates strategy performance |
| `requirements.txt` | Lists Python dependencies |

---

## ▶️ How to Run

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
