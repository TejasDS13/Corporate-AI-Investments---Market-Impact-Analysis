# Corporate AI Investments & Market Impact Analysis
Quantifying Stock Price Sensitivity to R&D, Revenues, and Strategic Milestones

## Project Overview
This repository contains a data science pipeline designed to evaluate how strategic corporate AI investments—specifically R&D expenditures and productized AI revenues—alongside major ecosystem milestone events, influence daily stock price metrics for leading tech firms (**OpenAI**, **Google**, and **Meta**).

Using a realistic, synthetic historical dataset, this project builds regression and event-study models to isolate the structural drivers behind market volatility and financial returns within the artificial intelligence sector.

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



Getting Started
Clone this repository to your machine.

Open the Jupyter Notebook inside VS Code or your local browser environment to review the steps.



### What changed:
Putting those three backticks (```) right below `└── README.md` closes the box cleanly, freeing up your headers (`## Dataset Schema` and `## Environment & Tech Stack`) so they display as clean, bold section titles instead of plain text inside the block. 

Swap that in, check the preview one more time, and you are ready to hit **Commit changes...**!
