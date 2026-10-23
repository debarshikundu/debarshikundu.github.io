---
title: "Tesla & GameStop Stock Dashboard"
summary: "IBM Data Science capstone: pulling stock and revenue data, then turning it into an interactive dashboard."
status: "Completed"
role: "Data analysis, visualisation"
stack: ["Python", "pandas", "Jupyter", "Plotly", "Web scraping"]
repo: "https://github.com/debarshikundu/TeslaAndGameStopStockAnalysisAndDashboard"
featured: true
order: 3
---

## The brief

The capstone asked a deceptively simple question: how do you compare a company's stock price with its actual revenue, and present that comparison to someone who does not want to read a notebook?

## What I built

A Jupyter-based analysis pipeline that collects historical stock data and revenue figures for **Tesla** and **GameStop**, cleans and aligns the two datasets, and renders the result in an interactive dashboard.

The interesting work was not the charting. It was reconciling data that arrives at different frequencies and in different shapes, and deciding what a fair comparison actually looks like.

## Process

1. **Collect** — pull stock history and scrape quarterly revenue.
2. **Clean** — normalise dates, handle missing periods, and document assumptions.
3. **Analyse** — compare price movement against revenue growth over the same window.
4. **Present** — build a dashboard that lets a reader explore the series instead of squinting at a static chart.

## What I took away

- Data cleaning is the majority of the job, and it is where the real decisions live.
- A dashboard is an argument. Every axis choice and default range nudges the reader toward a conclusion.
- Reproducibility matters: if the scrape breaks, the analysis should fail clearly rather than quietly drift.
