# 📊 PhonePe Transaction & User Behavior Analysis (2018–2021)

## Project Overview

This project analyzes digital payment trends using PhonePe transaction and demographic data across Indian states and districts. The objective is to uncover patterns in transaction growth, user behavior, and the relationship between demographics and digital adoption.

The analysis is performed using Python (Pandas, Matplotlib) in a Jupyter Notebook, covering multiple datasets including transactions, user activity, device usage, and population statistics.

## Dataset Description

The dataset consists of multiple sheets containing:
* State-level transactions and user data
* District-level transaction insights
* Transaction type splits (P2P, merchant, etc.)
* Device brand usage
* Demographic data (population, density)

Data quality is high, with minimal missing values (<0.3%), making it suitable for analysis.

## Key Analysis Performed
* Data cleaning and preprocessing
* Feature engineering (Year–Quarter trends)
* State-wise and district-wise aggregation
* Trend analysis using line plots
* Distribution analysis using bar and pie charts
* Correlation analysis between demographics and transactions

## Key Insights
* 📈 Rapid Growth: Transactions increased from 1.08B (2018) to 7.97B (2021), with total value rising from ₹1.6T to ₹14.6T
* 🌍 Regional Trends: Southern and western states dominate transaction volumes
* 💸 Transaction Behavior: Some low-volume or remote regions show higher average transaction value (ATV), indicating fewer but larger transactions
* 👥 User Influence: Registered users strongly correlate with transaction activity
* 📊 Demographics Impact: Population moderately influences usage, while population density has a limited effect

## Top & Bottom Performers

Top States by Transaction Volume
* Karnataka
* Maharashtra
* Telangana
* Andhra Pradesh
* Rajasthan

Lowest Transaction Volume
* Lakshadweep
* Andaman & Nicobar Islands
* Ladakh
* Mizoram
* Meghalaya

## Tools & Technologies
* Python
* Pandas
* Matplotlib
* Jupyter Notebook

## Conclusion

The analysis highlights the rapid adoption of digital payments in India, driven by increasing user base and transaction frequency. While highly populated states contribute the most to transaction volumes, smaller regions exhibit unique patterns such as higher transaction values, reflecting different usage behaviors.
