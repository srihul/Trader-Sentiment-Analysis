# Trader Behavior vs Market Sentiment Analysis

## Objective
Analyze how market sentiment (Fear/Greed) impacts trader performance and behavior.

## Data Sources
- Bitcoin Market Sentiment Dataset
- Historical Trader Data (Hyperliquid)

## Methodology
- Cleaned and preprocessed both datasets
- Converted timestamps and aligned data by date
- Merged datasets for combined analysis
- Analyzed key metrics like PnL and trade size

## Key Insights
1. Trader performance varies across sentiment, with Greed and Neutral showing higher variability.
2. Greed periods are associated with higher risk-taking behavior.
3. Fear periods show more consistent losses and unstable performance.
4. Extreme outliers indicate potential high-risk trades leading to significant losses.

## Strategy Recommendations
1. Reduce risk exposure during Greed periods.
2. Adopt a defensive and low-frequency trading approach during Fear periods.

## Tools Used
- Python
- Pandas
- Seaborn
- Matplotlib
