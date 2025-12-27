# DA-Final-Project
# FINANCIAL & MACROECONOMICS ANALYSIS

## 📌 1. Project Overview
This project provides a data-driven exploration of the relationship between financial markets and macroeconomic policy. By analyzing the **2000–2008 economic cycle**, the study identifies how central bank policies, consumer psychology, and national productivity intersect to drive market stability.

* **Domain:** Finance
* **Timeframe:** 2000 – 2008
* **Focus:** Market Forecasting, Macro Influence, and Risk Quantification.

## 🎯 2. Project Aims
1.  **Forecast** market trends using 50/200-day moving average crossovers.
2.  **Quantify** macro influence on stock prices and corporate profits.
3.  **Analyze** consumer confidence as a predictor of retail spending.
4.  **Develop** a risk dashboard to monitor economic stability zones.

## 📂 3. Dataset Overview
The analysis is based on a comprehensive dataset containing  **3,000 records** of daily and annual financial metrics:
* **Market Indices:** Daily Open/Close prices for S&P 500, Dow Jones, and NASDAQ.
* **Economic Indicators:** Annual GDP Growth (%), Inflation Rate (%), and Nominal Interest Rates.
* **Fiscal/Consumer Data:** Government Debt, Corporate Profits, Consumer Confidence Index (CCI), and Retail Sales volume.

## 🛠️ 4. Tools & Programs Used
The project was implemented using the **Python Data Science Stack**:
* **Pandas & NumPy:** Data manipulation, annual resampling, and grouped feature engineering.
* **Matplotlib & Seaborn:** Generation of 13 core visuals and regression plots.
* **Scipy/Statsmodels:** Polynomial regression for modeling volatility sensitivity.
* **Google Colab Notebooks:** Environment for Exploratory Data Analysis (EDA).

## ⚙️ 5. Methodology
* **Standardization:** Converted all fiscal metrics to USD and normalized date-time indices.
* **Feature Engineering:** Calculated **Grouped Returns** and **30-day Rolling Volatility** to isolate index-specific risk.
* **Trend Identification:** Applied **SMA 50/200** logic to detect long-term market regimes.
* **Aggregation:** Resampled daily fluctuations into annual means to reveal structural macroeconomic shifts.

---

## 📊 6. Key Findings

### Section 1: Financial Market Forecasting
* **Resilience:** Identified the **Dow Jones** as the era's primary stability benchmark ($+14\%$ growth).
* **Technical Signals:** Validated the **2003 Golden Cross** as a reliable precursor to the mid-decade expansion.


### Section 2: Macroeconomic Influence Quantification
* **The Profit Floor:** Established that sustainable corporate profit growth requires a **GDP growth floor of $\approx 3\%$**.
* **Policy Response:** Measured a structural **6–12 month lag** between inflation spikes and interest rate adjustments.

### Section 3: Consumer Behavior and Confidence
* **Predictive Power:** Proved that the **Consumer Confidence Index** serves as a statistically significant leading indicator for **Retail Sales**.
* **Sentiment Resilience:** Observed that consumer psychology often outweighs moderate interest rate hikes in driving spending.


### Section 4: Integrated Economic Risk Dashboard
* **The Stability Zone:** Defined the economic "Sweet Spot" as occurring when **Real Interest Rates are between $1\%$ and $3\%$**.
* **Risk Modeling:** Developed a "U-shaped" volatility curve demonstrating that extreme interest rate positions trigger market instability.


---

## 🚀 7. Final Conclusion
The project concludes that financial stability is a product of balanced monetary policy. When **Real Interest Rates** remain within the defined **$1\%$–$3\%$ Stability Zone**, market volatility is minimized, and the correlation between GDP and Corporate Profits is at its strongest.
