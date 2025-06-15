# quant-factor-prototype
Backtest prototype of momentum + mean reversion strategies using pandas &amp; matplotlib

# Quant Factor Prototype
This is my first quantitative project — a simple momentum + mean-reversion trading strategy backtested using Python, pandas and matplotlib.  
It serves as a foundational exercise in building, testing and visualizing trading ideas.

---

## Features

- **Data Source**: Yahoo Finance via `yfinance`
- **Indicators**:
  - 5-day Momentum (Price_t > Price_t−5)
  - 20-day Moving Average (for mean-reversion entry)
- **Strategy Logic**:
  - Buy when 5-day momentum is positive **and** price is below the 20-day MA
  - Hold for `n` days or until exit condition is triggered
- **Backtest**:
  - Basic daily-level vectorized backtest
  - Plots of cumulative return and drawdown
- **Visualization**:
  - Entry/exit points
  - Rolling performance

---

## Output Preview

> (Insert your chart here once project runs, e.g.)

![Backtest Result](plots/backtest_example.png)

---

## File Structure

