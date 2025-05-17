# Simple Trading Strategy Evaluation

This project compares three basic trading strategies—**coin flipping**, **momentum**, and **moving average crossovers**—using both synthetic simulations and historical data from TSLA, AAPL, BTC, and SPY (2022–2024).

## Strategies
- **Coin Flip:** Randomized buy/sell decisions.
- **Momentum (1, 2, 3-day):** Buy after consecutive up days, sell otherwise.
- **Moving Average Crossover:** Buy/sell based on short-term vs. long-term MA crossovers.

## Methodology
- Synthetic price paths generated via a multiplicative random walk.
- Historical data sourced using `yfinance`.
- Each strategy evaluated on cumulative P&L, Sharpe Ratio, win rate, and volatility.
- Jupyter notebooks provide all code and visuals.

## Key Findings
- **Momentum (1-day)** outperformed across most cases but with high volatility.
- **Moving Average** showed poor win rates and weak responsiveness.
- **Coin Flip** served as a neutral baseline—sometimes outperforming longer momentum signals.

## 📂 Files
- `Coin-Flipping Strategy.ipynb`
- `Momentum Strategy.ipynb`
- `Moving Average Strategy.ipynb`
- `Analysis Visualization.ipynb`
- `Comparative analysis.pdf` — full project report

## Future Improvements
Incorporate trading costs, slippage, stop-losses, dynamic sizing, and more realistic market models.

---

Let me know if you want this styled with badges, links to Colab, or instructions to run it locally.
