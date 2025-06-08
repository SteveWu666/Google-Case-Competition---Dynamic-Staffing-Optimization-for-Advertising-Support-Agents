# Google Case Competition 2025  
**Dynamic Staffing Optimization for Advertising Support Agents**

## Overview

This project presents a dynamic, month-by-month staffing model to optimize the allocation of advertising support agents across multiple countries. The goal is to balance cost efficiency, agent utilization, and incremental revenue, while ensuring timely support to eligible advertisers.

Developed as part of the 2025 Google Case Study Competition, the model addresses real-world operational constraints including agent capacity, hiring/firing lead times, and advertiser eligibility thresholds.

Our team won second place in this competition.

## Problem Statement

Google provides 60-day support to new advertisers who meet certain projected spending thresholds. Each support agent can manage up to 10 advertisers at any given time. However, daily fluctuations in advertiser sign-ups and agent lifecycle constraints make staffing planning non-trivial.

The challenge is to:
- Minimize cost from idle capacity and overstaffing
- Avoid advertiser wait time and drop-off
- Maximize incremental ad revenue through timely support

## Methodology

- **Eligibility Filtering**: Apply country-specific spending thresholds to classify eligible advertisers
- **Agent Pool Modeling**: Track advertiser support periods and agent utilization across time
- **Ramp-up & Firing Constraints**: Incorporate hiring delays and severance costs into staffing decisions
- **Simulation**: Run monthly simulations for 2025 to forecast agent demand and revenue outcomes
- **Sensitivity Analysis**: Test robustness of the staffing plan under high- and low-volume signup scenarios

## Data Sources

- Historical advertiser signup data (2023–2024)
- Country-specific agent salary and advertiser budget thresholds
- Probability-weighted uplift estimates for incremental ad revenue (0%–25%)

## Key Outputs

- Month-by-month optimal staffing plan by country
- Revenue and cost estimates under base and variant demand scenarios
- Recommendations for agent ramping strategies and hiring flexibility

## Tools Used

- Python (NumPy, pandas, matplotlib)
- Excel (intermediate modeling)
- Optimization heuristics and sensitivity simulation

## Authors

This project was developed by the **DeepAnalytics** team as part of the 2025 Google Case Competition.

**Team Members**:  
Corey Lin, Evelyn Liang, Huei-Sin Liu, Jim Cao, Jingwen Zhang, Qilian Wu, Shelly Wei

## License & Disclaimer

**Copyright © 2025  
DeepAnalytics Case Competition Team**

This repository is for academic and illustrative purposes only. Commercial use, redistribution, or unauthorized derivative work is strictly prohibited without explicit permission. All data and methods are synthetic or anonymized for competition purposes.
