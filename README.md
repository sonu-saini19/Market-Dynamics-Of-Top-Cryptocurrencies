# Market Dynamics of Cryptocurrencies

## Overview

The cryptocurrency market is one of the most volatile and rapidly evolving financial ecosystems. This project analyzes the historical performance of the **Top 20 Cryptocurrencies by Market Capitalization** to understand market behavior, return dynamics, volatility patterns, trading activity, and overall market structure.

Using exploratory data analysis, statistical testing, and risk assessment techniques, the project uncovers key insights into cryptocurrency market trends and identifies significant market events across multiple years.

---

## Project Objectives

- Analyze long-term cryptocurrency market trends.
- Evaluate price behavior and market capitalization growth.
- Compare volatility across leading cryptocurrencies.
- Measure risk and performance using return-based metrics.
- Identify bull and bear market phases.
- Examine relationships between price, volume, market capitalization, and volatility.
- Detect extreme market events using statistical techniques.
- Generate actionable insights through data visualization and statistical analysis.

---

## Dataset Information

The dataset contains historical cryptocurrency market data with the following attributes:

| Column | Description |
|----------|-------------|
| slug | Unique cryptocurrency identifier |
| symbol | Cryptocurrency ticker symbol |
| name | Cryptocurrency name |
| date | Trading date |
| ranknow | Market ranking |
| open | Opening price |
| high | Highest price of the day |
| low | Lowest price of the day |
| close | Closing price |
| volume | Trading volume |
| market | Market capitalization |
| close_ratio | Closing position within daily trading range |
| spread | Difference between daily high and low prices |

### Scope

To ensure meaningful analysis and avoid noise from low-cap assets, the dataset was filtered to the **Top 20 Cryptocurrencies by Market Capitalization**.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## Methodology

### Data Preparation

- Performed data exploration and quality assessment.
- Verified missing values and duplicate records.
- Conducted logical consistency checks on pricing data.
- Converted date columns for time-series analysis.
- Filtered the dataset to the Top 20 cryptocurrencies.

### Feature Engineering

Created additional analytical features including:

- Daily Returns
- 30-Day Rolling Volatility
- Yearly Performance Metrics
- Z-Score Based Outlier Detection

### Statistical Analysis

- Correlation Analysis
- Shapiro-Wilk Normality Test
- Return Distribution Analysis
- Volatility Analysis
- Outlier Detection

---

# Key Visualizations

## 1. Top 10 Cryptocurrencies by Market Capitalization

<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/4c800c84-7118-417d-968a-80db2aa21957" />

### Insight
A small number of cryptocurrencies dominate the overall market capitalization, indicating a highly concentrated market structure.

---

## 2. Historical Market Capitalization Trends

<img width="1391" height="690" alt="image" src="https://github.com/user-attachments/assets/2efa2b78-af2a-4ebc-b160-e4bf7b2d013e" />


### Insight
Leading cryptocurrencies demonstrated substantial long-term growth despite periods of market corrections and elevated volatility.

---

## 3. Daily Return Distribution

<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/23124770-7bd4-46d3-b178-b39fa4f0fc54" />


### Insight
Most daily returns are concentrated around zero, while the presence of heavy tails indicates occasional extreme gains and losses.

---

## 4. Rolling Volatility Analysis

<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/b9cec8e1-057b-4c38-8672-500ca3cd6f73" />


### Insight
Volatility spikes correspond to periods of significant market uncertainty and major price movements.

---

## 5. Correlation Heatmap

<img width="705" height="590" alt="image" src="https://github.com/user-attachments/assets/7ed92c3d-fbb9-40de-b8e7-3e33e61cf51c" />


### Insight
Market capitalization and trading volume exhibit a strong positive correlation, while most other relationships remain relatively weak.

---

## 6. Volatility Comparison Across Cryptocurrencies

<img width="1386" height="689" alt="image" src="https://github.com/user-attachments/assets/f16bd120-afe9-4af2-aaf1-3c55206e1049" />
### Insight
Risk levels vary significantly among major cryptocurrencies, demonstrating different volatility profiles across assets.

---

# Statistical Results

## Shapiro-Wilk Normality Test

| Metric | Value |
|----------|----------|
| p-value | 6.81 × 10⁻⁸⁵ |

### Conclusion

The null hypothesis was rejected, indicating that cryptocurrency daily returns do not follow a normal distribution.

---

## Z-Score Outlier Detection

| Metric | Value |
|----------|----------|
| Extreme Return Events | 18 |

### Conclusion

Only a small number of statistically significant extreme return events were identified, representing rare but impactful market movements.

---

# Key Findings

### Market Structure

- Trading volume and market capitalization showed a strong positive correlation (**0.88**).
- Market value is heavily concentrated among a limited number of leading cryptocurrencies.

### Price Dynamics

- Closing price and daily price spread demonstrated a strong positive relationship (**0.75**).
- Higher-valued cryptocurrencies generally experienced larger daily price ranges.

### Return Characteristics

- Cryptocurrency returns were found to be non-normally distributed.
- Return distributions exhibit heavy tails and extreme market behavior.

### Risk Analysis

- Significant differences in volatility were observed across the analyzed cryptocurrencies.
- Volatility remains one of the defining characteristics of digital asset markets.

### Market Cycles

- **2017** represented the strongest bullish phase within the dataset.
- **2018** reflected a major market correction following the 2017 rally.

### Extreme Events

- Z-score analysis identified only **18 extreme return events**, highlighting the rarity of significant market shocks.

---

# Business Insights

- Larger cryptocurrencies attract significantly greater trading activity.
- Market leaders continue to dominate overall market capitalization.
- Cryptocurrency returns exhibit asymmetric risk characteristics.
- Bull markets are often followed by sharp correction phases.
- Volatility profiles differ substantially even among top-ranked cryptocurrencies.
- Data-driven risk assessment is essential when evaluating cryptocurrency investments.

---

# Conclusion

This project provides a comprehensive analysis of the **Top 20 Cryptocurrencies**, focusing on market trends, volatility, returns, and statistical market behavior. Through exploratory data analysis, volatility modeling, correlation analysis, and statistical testing, the study reveals the highly dynamic nature of cryptocurrency markets.

The findings demonstrate that cryptocurrency markets are characterized by significant volatility, non-normal return distributions, occasional extreme events, and rapidly evolving market conditions. While leading cryptocurrencies exhibit substantial long-term growth, their risk profiles vary considerably, emphasizing the importance of quantitative analysis when assessing digital assets.

---

## Author

**Sonu Saini**
