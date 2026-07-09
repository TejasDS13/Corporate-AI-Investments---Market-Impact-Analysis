# Corporate AI Investments & Market Impact Analysis
Quantifying Stock Price Sensitivity to R&D, Revenues, and Strategic Milestones

## Project Overview
This repository contains a data science pipeline designed to evaluate how strategic corporate AI investments—specifically R&D expenditures and productized AI revenues—alongside major ecosystem milestone events, influence daily stock price metrics for leading tech firms (**OpenAI**, **Google**, and **Meta**).

Using a realistic, synthetic historical dataset, this project builds regression and event-study models to isolate the structural drivers behind market volatility and financial returns within the artificial intelligence sector.

## Key Features & Objectives
* **Investment Sensitivity Analysis:** Quantify the statistical relationship between daily R&D allocation (`R&D_Spending_USD_Mn`), product revenue generation (`AI_Revenue_USD_Mn`), and immediate market valuation fluctuations.
* **Event Study Framework:** Map out explicit milestone intervals (`Event`) to evaluate abnormal returns and localized market trends immediately surrounding core product updates and strategic releases.
* **Feature Engineering & Exploration:** Process historical financial indicators to clear data anomalies, balance features, and visualize cross-company performance anomalies.

## Repository Structure
```text
├── AI_Financial_and_Market_Impact_Analysis.ipynb  # Primary data analysis pipeline
├── ai_financial_market_daily_realistic_synthetic.csv  # Sourced/engineered dataset
└── README.md                                          # Documentation

Dataset Schema
The pipeline ingests a dense time-series asset tracking dataset featuring:

Date: Timeline sequence tracking financial metrics.

Company: Target entities under analysis (OpenAI, Google, Meta).

R&D_Spending_USD_Mn: Daily adjusted corporate research and development investment metrics.

AI_Revenue_USD_Mn: Isolated, product-specific artificial intelligence income streams.

AI_Revenue_Growth_%: Rolling percentage growth margins for target sectors.

Event: Contextual markers representing product drops, system updates, or structural breakthroughs.

Stock_Impact_%: The dependent performance metric measuring downstream price sensitivity.



Environment & Tech Stack
Python 3.x

Pandas & NumPy (Data manipulation and mathematical processing)

Matplotlib & Seaborn (Statistical visualization and correlation tracking)
