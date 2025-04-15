# Pump.Fun Serial Deployers Analysis

## Overview

This repository contains comprehensive data analysis and research on token deployers within the Solana ecosystem, specifically focusing on activities related to Pump.fun platform. The analysis examines patterns of token deployment, "rugging" behaviors, and their impact on the ecosystem.

[Link to Full Article]()

## Topics Covered

- In-depth analysis of growth trends and patterns
- Identification and profiling of key actors in token deployment
- Assessment of deployment volumes and methodologies
- Analysis of wallet bundling strategies
- Actionable recommendations for ecosystem security
## Repository Structure

### Data and Analysis
- `sources.ipynb`: Contains all numbered figures and statistics referenced in the article
- `data_collection.ipynb`: Documents the methodology and processes used for data collection
- `top100_creators.csv`: Aggregated statistics of the top 100 most prolific coin deployers

### Dataset Description

The `top100_creators.csv` file contains aggregated statistics for each token deployer, including:

| Column | Description |
|--------|-------------|
| num_tokens | Number of tokens deployed by each address |
| mean_time_delta | Average time between token deployments |
| seconds_to_dump | Average duration from token inception to complete dumping |
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

The analysis concludes with 2 recommendations for the Pump.fun ecosystem to:

1. build a user-facing tool that allows for quick information about a token's creator 

2. build an opt-in customizable token vesting tool which will allow creators to signal the intent of their coin deployment

implementing both of these recommendations will:   

- Mitigate the impact of serial deployers
- Reduce prevalence of malicious actors
- Enhance overall platform security
- Improve user trust and safety




## Potential entities and the addresses they control

### ESK_NFT
- MNhBbrscBPmeid54buiqSgyWa4D8PY6uKHoK2wJsTJN
- 6d22FozaKK239PoBYVffkYKA1QPQZE8fC7AQkpmHQfjp
- 36DWP52MVRDooYNrcRVDyoCh2R1fPXCYqKJQYg9pFQoE
- 83QQFLxcEzuJZaejBnzAiW5tyfyaRHMLZnkhJbRPRWtf
- B8xTCohpTmuR57pJ8ucKPZfBjdw3Lfkvii4deXRRrL4H
- 5Hyf6srdbrrD1HLjqxcFbXJRFBHgnwoZc7aZRj8vDuk5
- C88rn1cz1PcRJFh44TuynaWbnRis4xuBRi65sD1Nwxog
- D3sovmjANgA8V27e5rnQft8kV3mocSH8gw9zwth3Ba9g
- BfAgS1vsK2Wja56zxcBrMMdn6sFgTnMmZu3wi4XwiAt3
- 3mL9kH1KqbpFcY9Ry5u9xfZuTSiA2BDTUC6CX9GTLs2w



## 60s exiter 
- BEnGowz22N6QtVdBCqG53FzYGdPhBqSZmPD3aCgnq4NM
- 9RaEEUfFwbzNSA6qBpYzew67xBehfT4soKbUR5KuQNJf
- 3rYj2dThkPHXxX8UNyT6361dqpeQaAU2g3mpZrEwRbnM
- 4RePs4EchMosyRENfkUFwZcjgMsdTt9SzYMZomtvRQEi


## Bimodal exiter 
- DUKVDysvzUK5tdfe1Y3kShdEtgHy7j92caUHSHHrECiW
- 7m6zpeapVnx52JLqrcEsp56XXN6skUeWMZDUFzDjE2yC
- Bx7SLBFceTJLrqcBFisb5NmmFCFtXQSm4o1oYpCHuhB9
- 21qj6yRo17y96vFrYEo5dKtgR6HjqW4Adim2XYDMv2CN
