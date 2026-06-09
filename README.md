# 📈 Structural Breaks in Cointegrating Relationships: Gregory–Hansen Test Applications

## Overview

This project investigates whether long-run equilibrium relationships among key U.S. macroeconomic variables remain stable during major economic shocks and policy regime changes. Using quarterly data from 2000–2024, the study applies advanced time-series econometric techniques to identify structural breaks, estimate long-run cointegrating relationships, and evaluate short-run adjustment dynamics.

The analysis incorporates multiple structural-break methodologies to account for events such as the Dot-Com Recovery, Global Financial Crisis, Quantitative Easing Period, COVID-19 Pandemic, and Post-Pandemic Inflation Shock. :contentReference[oaicite:1]{index=1}

---

## Research Objective

The project aims to:

- Examine long-run relationships among GDP, inflation, interest rates, and exchange rates.
- Detect endogenous structural breaks in macroeconomic time series.
- Compare traditional cointegration methods with structural-break-adjusted models.
- Measure short-run and long-run economic adjustment mechanisms.
- Evaluate how major economic crises alter macroeconomic equilibrium relationships. :contentReference[oaicite:2]{index=2}

---

## Dataset

### Source
Federal Reserve Economic Data (FRED API)

### Time Period
2000Q1 – 2024Q4

### Frequency
Quarterly

### Variables

| Variable | Description |
|-----------|------------|
| LRGDP | Real Gross Domestic Product (Log) |
| LREX | USD/EUR Exchange Rate (Log) |
| R | Federal Funds Rate |
| LCPI | Consumer Price Index (Log) |

The dataset contains approximately 100 quarterly observations covering multiple economic cycles and crisis periods. :contentReference[oaicite:3]{index=3}

---

## Econometric Framework

### 1. Stationarity Analysis

Applied:

- Augmented Dickey-Fuller (ADF) Test
- Unit Root Diagnostics

Purpose:

- Determine integration order
- Verify suitability for cointegration analysis

---

### 2. Structural Break Detection

Implemented:

#### Zivot–Andrews Test

Identifies endogenous structural breaks in:

- GDP
- Exchange Rates
- Interest Rates
- Consumer Prices

Detected major break periods associated with:

- Global Financial Crisis
- Oil Price Shock
- COVID-19 Pandemic

---

### 3. Cointegration Analysis

#### Johansen Cointegration Test

Used to identify long-run equilibrium relationships among multiple macroeconomic variables.

#### Gregory–Hansen Cointegration Test

Models estimated:

- Level Shift (C)
- Regime Shift (C/S)
- Regime and Trend Shift (C/S/T)

The strongest evidence of cointegration was found under the regime-and-trend-shift specification, indicating that equilibrium relationships persisted despite major structural changes. :contentReference[oaicite:4]{index=4}

---

### 4. Multiple Structural Break Analysis

#### Bai–Perron Test

Detected structural breaks around:

- 2003Q3
- 2008Q4
- 2013Q1
- 2015Q3
- 2020Q1
- 2022Q1

These periods correspond to major economic and policy transitions in the U.S. economy. :contentReference[oaicite:5]{index=5}

---

### 5. Error Correction Model (ECM)

Estimated:

- Long-run equilibrium equation
- Short-run adjustment mechanism
- Error Correction Term (ECT)

Findings indicate:

- Significant convergence toward equilibrium
- Approximately 11% adjustment per quarter
- Inflation and interest rates significantly influence short-run GDP dynamics

while exchange-rate effects remain comparatively weak. :contentReference[oaicite:6]{index=6}

---

## Key Findings

### Long-Run Results

- GDP, inflation, exchange rates, and interest rates exhibit long-run equilibrium relationships.
- Consumer prices are the dominant long-run determinant of GDP.
- Exchange rates have a weak negative long-run effect.
- Interest rates are statistically insignificant in the long-run equation.

### Structural Break Results

Major breaks coincide with:

- Dot-Com Recovery
- Global Financial Crisis
- Quantitative Easing Period
- COVID-19 Pandemic
- Post-Pandemic Inflation Regime

### Short-Run Results

- Inflation significantly impacts GDP growth.
- Interest-rate changes affect output dynamics.
- Economic shocks are temporary and gradually corrected through the equilibrium mechanism.

---

## Technologies & Tools

### Programming

- R

### Data Sources

- FRED API

### Econometric Packages

- quantmod
- urca
- strucchange
- tsDyn
- tseries
- dynlm
- lmtest
- sandwich
- car
- ggplot2
- tidyverse

### Techniques

- Time Series Analysis
- Unit Root Testing
- Cointegration Analysis
- Gregory–Hansen Test
- Johansen Test
- Bai–Perron Structural Break Analysis
- Error Correction Modeling
- Macroeconomic Forecasting Frameworks

---

## Business & Policy Relevance

Understanding structural breaks is critical because traditional econometric models often assume stable relationships over time. Ignoring regime shifts can lead to biased estimates, inaccurate forecasts, and ineffective policy decisions.

This framework provides policymakers, economists, and financial analysts with a more realistic approach to modeling economies exposed to crises, policy changes, and external shocks. :contentReference[oaicite:7]{index=7}

---

## Skills Demonstrated

- Advanced Econometrics
- Time Series Modeling
- Structural Break Detection
- Cointegration Analysis
- Error Correction Models
- Macroeconomic Research
- Statistical Programming in R
- Quantitative Economic Analysis
- Financial Econometrics
- Economic Policy Evaluation
