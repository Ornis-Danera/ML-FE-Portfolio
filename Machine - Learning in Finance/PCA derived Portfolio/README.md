## Overview
This mini project explores the behavior of currency portfolios derived from Principal Component Analysis (PCA).  
Rather than interpreting PCA factors as market signals or hedging strategies, the focus here is on testing how persistent the top-performing principal components are across consecutive quarters.

By comparing the portfolios associated with the highest-returning components from one quarter to the next, this analysis provides insight into how quickly the structure of currency returns evolves over time — revealing whether strong components remain stable or rotate rapidly with changing market conditions.

## Data
- Daily or monthly currency exchange rates against USD.
- Returns computed as log changes over time windows.
- Grouped by quarters for temporal persistence analysis.

## Methods
- Standardized returns.
- Applied PCA to each quarterly segment.
- Identified the component portfolios with the highest average return.
- Compared portfolio persistence across quarters.

## Tools
- Python (NumPy, Pandas, Matplotlib, Scikit-learn)

## Key Insight
Investigates how currency return structures evolve — whether dominant return factors persist or shift with market regimes.

