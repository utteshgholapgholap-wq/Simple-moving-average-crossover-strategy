# Simple-moving-average-crossover-strategy

```markdown
# The Trend Follower: Moving Average Crossover Strategy

A clean, production-ready Python implementation of the classic **Moving Average Crossover** momentum strategy using `pandas` and `numpy`. 

This strategy is one of the pillars of algorithmic trend-following. It triggers a **BUY** signal when a short-term (fast) moving average crosses above a long-term (slow) moving average, indicating upward momentum. Conversely, it triggers a **SELL** signal when the fast moving average crosses below the slow moving average, indicating downward momentum.

---
## 🚀 Features

- **Vectorized Execution:** Uses highly optimized `pandas` and `numpy` operations instead of slow loops, making it suitable for massive historical datasets.
- **Dynamic Windows:** Easily configure custom periods for both the fast and slow moving averages (e.g., 50/200 day, 9/21 day).
- **Tristate Signals:** Clear, actionable numeric outputs:
  - ` 1` = **BUY** (Golden Cross)
  - `-1` = **SELL** (Death Cross)
  - ` 0` = **HOLD** / No action


---

## 🛠️ Prerequisites

Ensure you have the core Python data science stack installed:

```bash
pip install pandas numpy
