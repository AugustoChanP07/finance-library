# 📊 Finance Library: Portfolio Risk & Optimization Toolkit

A Python toolkit for financial analysis, portfolio optimization, and risk modeling — built to apply financial theory through clean, modular, data-driven code.

Rather than relying on black-box functions, this project breaks down each financial concept (Monte Carlo simulation, CAPM, Markowitz optimization) into transparent, reusable components — so every number in the output can be traced back to the logic behind it.

---

## 🚀 Features

- **Data Retrieval** — pull historical prices, returns, and benchmark data
- **Performance Analysis** — returns, volatility, Sharpe ratio
- **Risk Modeling** — beta, Value at Risk (VaR), Conditional VaR (CVaR)
- **Monte Carlo Simulations** — project portfolio outcomes under thousands of random scenarios
- **CAPM** — estimate expected returns based on systematic risk
- **Markowitz Optimization** — build the efficient frontier and find optimal portfolio weights

---

## 🧠 Why this project

Most finance libraries hide the math behind pre-built functions. This project was built to deeply understand *how* these models work — from simulating thousands of possible market paths in a Monte Carlo simulation, to solving for the optimal risk-return tradeoff in Markowitz's efficient frontier — while keeping the code modular enough to reuse in real analysis.

---

## 🛠️ Tech Stack

- Python (pandas, numpy, matplotlib)
- Jupyter Notebooks
- (Add here: yfinance / any API used for data retrieval, scipy for optimization, etc.)

---

## 📈 Example Usage

```python
from finance_library import PortfolioEngine

# Load portfolio data
portfolio = PortfolioEngine(tickers=["AAPL", "MSFT", "GOOGL"], start="2020-01-01")

# Run Monte Carlo simulation
results = portfolio.monte_carlo_simulation(n_simulations=10000, horizon_days=252)

# Get optimal Markowitz weights
optimal_weights = portfolio.optimize_portfolio(method="markowitz")
```

*(Ajusta este bloque a tu API real — nombres de clases/funciones tal como están en tus notebooks)*

---

## 📊 Sample Output

*(Aquí agrega una imagen: la distribución de resultados del Monte Carlo, o la curva de la frontera eficiente — son las gráficas más "vendedoras" de este tipo de proyecto)*

---

## 📂 Project Structure
