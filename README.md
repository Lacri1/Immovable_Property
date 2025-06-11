# Seoul Apartment Price Analysis and Economic Policy Impact

## Project Overview
This project analyzes the trends in Seoul apartment prices from 2013 to 2023 and examines the impact of economic policies (base interest rates, mortgage rates, etc.) on the real estate market. The analysis provides valuable insights into the relationship between macroeconomic policies and housing market dynamics in Seoul.

## Installation
```bash
pip install PublicDataReader pandas matplotlib seaborn numpy
```

## Key Analysis

### 1. Apartment Price Index and Jeonse Price Ratio Trends
- Visualized the changes in Seoul's apartment price index and jeonse (key money) price ratio from 2013 to 2023
- Price index showed a continuous upward trend since 2017, peaking in 2022 before starting to decline
- Jeonse price ratio peaked in 2017, declined, and has recently shown signs of recovery

### 2. Base Rate and Mortgage Rate Analysis
- Base rate fluctuated from 2.5% in September 2013 to 3.5% in November 2023
- The low-interest period of 2020-2021 correlated with a significant surge in housing prices
- Post-2022 interest rate hikes coincided with a market downturn

### 3. Buyer's Market Index
- High buyer's market index observed in 2015 and 2020-2021
- Strong correlation between buyer's market index and actual price movements
- Recent decline in the index indicates market cooling

### 4. Transaction Volume Analysis
- Transaction volume decreased from approximately 8,500 cases in 2013 to below 3,000 in 2023
- Sharp decline observed post-2022
- Direct correlation between interest rate hikes and reduced transaction volumes

## Key Findings
1. **Interest Rate Impact**: Clear inverse relationship between interest rate changes and housing prices
2. **Market Sentiment**: Buyer's market index serves as a leading indicator of market movements
3. **Volume-Price Relationship**: Declining transaction volumes typically precede price corrections
4. **Policy Lag**: 3-6 month lag observed between policy implementation and market impact

## Data Sources
- KB Real Estate Statistics
- Bank of Korea Base Rate Data
- Seoul Metropolitan Government Real Estate Transaction Data
- PublicDataReader API for real-time data collection
