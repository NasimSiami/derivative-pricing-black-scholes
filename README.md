# 🧮 Derivative Pricing with the Black-Scholes Model

This project implements a dynamic hedging strategy using European put options priced via the Black-Scholes formula. The strategy evaluates the cost of insuring against downside risk in a currency position over a 1-year horizon.

---

## 🎯 Objective
To calculate the total cost of a hedge composed of monthly European puts on CAD/USD, using Black-Scholes pricing and various macro-financial parameters.

---

## 📈 Methods
- Implemented the Black-Scholes formula for European put pricing
- Simulated option values at monthly intervals (12 periods)
- Aggregated total cost of all puts as a proxy for hedge cost
- Analyzed how time, volatility, and rates affect pricing

---

## 📊 Parameters Used
- Spot exchange rate (x₀), strike (K)
- Volatility (σ = 10%)
- Domestic and foreign interest rates (r = 2%, rf = 1%)
- 12-month hedge horizon, evaluated monthly

---

## 🧰 Tools & Libraries
- Python (NumPy, pandas, SciPy, matplotlib)
- Black-Scholes formula
- Custom simulation of hedging timeline
