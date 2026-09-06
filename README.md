# Global Economic Indicators Pipeline

This repository contains an automated Python data pipeline and visual analytical models querying macroeconomic indicators directly from the World Bank API.

## Current Module: Real GDP Growth Comparison

- **Source:** World Bank Open Data API (`NY.GDP.MKTP.KD.ZG`)
- **Target Metrics:** Real GDP Growth Rate (%)
- **Regions Tracked:** Iraq, Saudi Arabia, Türkiye, Russia, Germany
- **Timeframe:** 2015 – 2025
- **Tooling:** Python (`pandas`, `requests`, `plotly`)

### Execution
The data ingestion script is hosted and executable via Google Colab:
- View Notebook: [`notebooks/GDP_Growth_Analysis.ipynb`](./notebooks/GDP_Growth_Analysis.ipynb)
