# 📊 Cryptocurrency Portfolio Management and Diversification

This project demonstrates a **comprehensive approach to managing and optimizing cryptocurrency portfolios**, focusing on **diversification, risk assessment, and market efficiency**.  
Implemented in Python using object-oriented programming (OOP) principles, it blends quantitative finance concepts with practical portfolio simulations.

---

## 🧠 Introduction

In the dynamic realm of cryptocurrency portfolio management, achieving **optimal diversification** is crucial due to the **volatile and interconnected nature** of digital assets.  

Selecting assets and determining their optimal weights is challenging. This project integrates **technical and predictive analyses** to construct portfolios based on an investor's **risk appetite**, leveraging both theoretical finance concepts and practical programming.

We focus on:

- Portfolio management and diversification  
- Risk pricing and market efficiency  
- Object-oriented implementation of financial concepts  
- Visualization of portfolios, efficient frontiers, and market lines  

---

## 📘 Project Plan

1. **Introduction**  
2. **Selected Assets**  
   - Portfolio assets  
   - Market index  
3. **Data Import and Preparation**  
   - Data extraction from major exchanges  
   - APIExtractor and DateHelpers classes  
   - CandlestickParser and SpotServices classes  
4. **Portfolio Management and Diversification**  
   - Portfolio basic concepts  
   - Random portfolios simulation  
   - Efficient frontier and Markowitz mean-variance optimization  
   - Capital Market Line (CML)  
   - Market portfolio construction  
   - Different portfolio types (Risk-optimal, Minimum risk, Risk appetite)  
   - Diversification metrics (Mean variance, Mean covariance)  
5. **Risk Price and Market Efficiency**  
   - Linear regression model for Beta and SML  
   - Systematic and specific risk decomposition  
   - Security Market Line simulation  
   - Performance measures: Treynor ratio, Sharpe ratio, Jensen index  

---

## ⚙️ Technologies Used

- **Python**: requests, datetime, time, numpy, pandas, matplotlib, scipy, statsmodels  
- **OOP Implementation** for portfolio, market, and risk classes  
- **Data visualization** for portfolios, efficient frontiers, and risk-return analyses  

---

## 📊 Assets and Data

The project uses **selected cryptocurrencies** (e.g., BTC, ETH, others) and calculates:

- **Asset returns and volatility**  
- **Covariance matrix among assets**  
- **Random portfolios** generation and sorting by return  
- **Efficient frontier** construction and optimal portfolio weights  

---

## 📈 Portfolio Construction

- **Random Portfolios Simulation**: Generates portfolios and visualizes return vs risk  
- **Markowitz Mean-Variance Optimization**: Computes optimal weights for assets based on risk and return  
- **Different Portfolio Types**: Risk-optimal, Minimum risk, and Risk appetite portfolios  

---

## 📉 Risk and Market Efficiency

For each asset, the project calculates:

- **Beta** (systematic risk) and classifies as aggressive, defensive, or neutral  
- **Total risk, systematic risk, specific risk**  
- **Plots of total risk vs returns**  

Market index construction and Capital Market Line (CML):

- Trace CML using BTC and ETH as major components  
- Compare CML vs random portfolios  
- Compare CML vs efficient frontier  

---

## 📊 Diversification Metrics

- **Mean-variance ratio**  
- **Mean-covariance ratio**  
- Comparison of diversification between portfolios  

---

## 📈 Security Market Line (SML) and Performance Measures

- Construct SML and plot assets (Beta vs Expected Return)  
- Calculate portfolio performance metrics:  
  - **Treynor ratio**  
  - **Sharpe ratio**  
  - **Jensen index**  

---
# ⚙️ Technical Details

## 🚀 How to Run the Notebook

1. Clone the repository:

```bash
git clone https://github.com/IHEBT-DEV/Portfolio_managementV1.git
```

2. Install required packages:

```bash
pip install requests numpy pandas matplotlib scipy statsmodels
```

3. Open the notebook in **Google Colab** or **Jupyter Notebook**:

```bash
jupyter notebook Portfolio_management_and_diversification.ipynb
```

4. Run all cells sequentially. Modify parameters (assets, portfolio types, risk appetite) as needed.  

---

## 📂 Repository Structure

```
Portfolio_managementV1/
│
├── Portfolio_management_and_diversification.ipynb      # Main Colab notebook
└── README.md                                           # Project documentation
```

---
## 💡 Key Insights

- Random portfolio simulations provide a clear picture of **risk-return trade-offs**.
- Markowitz optimization effectively identifies **efficient portfolios** for different risk appetites.
- CML and SML help assess **market efficiency** and individual asset performance relative to the market.
- Diversification metrics show how **interdependence among assets** can reduce overall portfolio risk.
- Cryptocurrencies exhibit high volatility; proper portfolio weighting is critical to **risk management**.

---

## 🚀 Future Improvements

- Include **additional cryptocurrency assets** to improve diversification analysis.
- Implement **dynamic portfolio rebalancing** based on market conditions.
- Incorporate **more advanced risk models**, such as CVaR (Conditional Value at Risk).
- Add **interactive visualizations** for efficient frontier and CML using Plotly or Bokeh.
- Integrate **real-time API data** for live portfolio monitoring and alerts.

---

## 💡 Conclusion

This project provides a **hands-on framework** for cryptocurrency portfolio management:

- Integrates **random portfolio simulations**, **efficient frontier analysis**, and **CML construction**
- Evaluates **asset risk and market efficiency**
- Demonstrates **portfolio performance metrics**
- Offers a **practical OOP implementation** of financial models for real-world use


---

## 🧑‍💻 Author

**Iheb T**  
Quantitative Developer & Research Enthusiast  
Focused on simulation methods, stochastic modeling, and quantitative finance
📂 GitHub: [IHEBT-DEV](https://github.com/IHEBT-DEV)  
💼 LinkedIn: [linkedin.com/in/iheb-touati](https://linkedin.com/in/iheb-touati)

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

> **"Volatility is inherent in crypto markets — smart portfolio design ensures risk is deliberate, not chaotic."**
