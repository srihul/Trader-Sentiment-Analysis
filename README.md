# Trader Sentiment Analysis

## Objective
Analyze how market sentiment (Fear/Greed) impacts trader behavior and performance.

## Dataset

The datasets used in this project are provided below:

- Fear/Greed Index Dataset: https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view
- Historical Trader Data: https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view

Note: Due to file size limitations, datasets are not uploaded to this repository.

## Methodology
- Cleaned and preprocessed both datasets
- Converted timestamps and aligned data by date
- Merged datasets on date
- Analyzed trader performance using:
  - Closed PnL
  - Trade size (USD)
- Visualized patterns using boxplots

## Key Insights
1. Trader performance varies across sentiment, with Greed and Neutral showing higher variability.
2. Greed periods are associated with higher risk-taking behavior.
3. Fear periods show more consistent losses and unstable performance.
4. Extreme outliers indicate high-risk trades leading to significant losses.

## Strategy Recommendations
1. Reduce risk exposure during Greed periods to avoid large losses.
2. Adopt a defensive and low-frequency trading approach during Fear periods.

## How to Run
1. Clone the repository
2. Install dependencies:
   pip install pandas matplotlib seaborn
3. Run the notebook:
   jupyter notebook
