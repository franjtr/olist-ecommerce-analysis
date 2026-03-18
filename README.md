# Olist E-Commerce: Strategic Insights & Statistical Analysis

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Scipy](https://img.shields.io/badge/Stats-SciPy-green.svg)](https://scipy.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Executive Summary
This project provides a comprehensive data-driven audit of **100,000+ anonymized orders** from Olist (2016–2018). Beyond simple visualization, the analysis applies **Statistical Hypothesis Testing** to quantify the "Expectation Gap" in logistics and its direct impact on brand reputation and customer retention.

## Key Business Insights
* **The Black Friday Pivot:** The November 2017 spike was not just a seasonal peak; it permanently established a **new monthly revenue baseline**, signaling a structural expansion of the platform's market share.
* **Logistics Penalty:** A **Late Delivery** isn't just a delay; it's a **49% drop in satisfaction** (from 4.29 to 2.27 stars).
* **Geographic Dependency:** High concentration in the Southeast region, with São Paulo (SP) alone accounting for **38.28% of total revenue**.
* **Statistical Rigor:** Identified and explained data anomalies in short-term deliveries (3-4 days) through **sample size auditing**, ensuring business insights remained statistically representative.

## Tech Stack & Methodology
* **Data Ingestion & Cleaning:** Python (Pandas, NumPy) for merging 8+ relational tables and handling Portuguese-to-English category mapping.
* **Statistical Validation:** Used **SciPy (T-Tests)** to confirm that the correlation between delivery delays and low review scores is statistically significant ($p < 0.001$, $T=100.9$).
* **Time Series:** Resampling and seasonal analysis to detect growth trajectories and holiday impacts.
* **Visualization:** Seaborn and Matplotlib (Violin plots for distribution density, Time-series decomposition).

## Analysis Architecture
1.  **Revenue Drivers:** Identification of Top 10 categories (Health & Beauty leading with R$ 1.2M+).
2.  **Growth Trajectory:** Time-series analysis focusing on consistent data from Jan 2017 to Aug 2018.
3.  **Spatial Distribution:** Geographic mapping of sales by Brazilian states and regional concentration.
4.  **Logistics Audit:** Measuring the Average Delivery Time (12.09 days) and Failure Rate (6.77% late).
5.  **The Expectation Gap:** Quantifying the "penalty" of broken delivery promises vs. customer rating.


