# Pump.Fun Serial Deployers Analysis

## Overview

This repository contains comprehensive data analysis and research on token deployers within the Solana ecosystem, specifically focusing on activities related to Pump.fun platform. The analysis examines patterns of token deployment, "rugging" behaviors, and their impact on the ecosystem.

[Link to Full Article]()

## Topics Covered

- In-depth analysis of growth trends and patterns
- Identification and profiling of key actors in token deployment
- Assessment of deployment volumes and methodologies
- Analysis of wallet bundling strategies
- Investigation of validator involvement
- Actionable recommendations for ecosystem security
## Repository Structure

### Data and Analysis
- `sources.ipynb`: Contains all numbered figures and statistics referenced in the article
- `data_collection.ipynb`: Documents the methodology and processes used for data collection
- `top100_creators.csv`: Comprehensive dataset of the top 100 most prolific coin deployers

### Dataset Description

The `top100_creators.csv` file contains aggregated statistics for each token deployer, including:

| Column | Description |
|--------|-------------|
| num_tokens | Number of tokens deployed by each address |
| mean_time_delta | Average time between token deployments |
| seconds_to_dump | Duration from token inception to complete dumping |
| sol_pnl | Profit and loss (SOL) |
| usd_pnl | Profit and loss (USD) |
| total_sol_volume | Trading volume (SOL) |
| total_usd_volume | Trading volume (USD) |
| num_swappers | Unique addresses that transacted with the coin |
| creator_from_sol_swaps | Number of swaps from SOL to created token |
| creator_to_sol_swaps | Number of swaps from created token to SOL |
## Technical Notes

The data collection methodology was optimized to minimize API usage. While this approach served the research purposes, more efficient queries could be developed for user-facing tools as recommended in the article.

## Recommendations

The analysis concludes with actionable insights for the Pump.fun ecosystem to:
- Mitigate the impact of serial deployers
- Reduce prevalence of malicious actors
- Enhance overall platform security
- Improve user trust and safety

