# Applications of Graph Theory in Indian Market Analysis

**Author: Sohum Muley**

This quantitative research report is based on Joseph Attia's paper "The Applications of Graph Theory to Investing," adapted for the Indian market using Nifty 50 as the stock universe.

## Main Idea

The study focuses on constructing portfolios based on stock correlations using graph theory. Two types of portfolios are explored: higher correlation and lower correlation portfolios. The portfolios are created using a 4-year back window and held for 4 years before rebalancing.

## Portfolio Construction

Graphs are constructed with stocks as nodes and correlations as edges. For the higher correlation portfolio, nodes with correlations above a threshold (0.46) are connected, and for the lower correlation portfolio, nodes with correlations above a threshold (0.33) are connected.

## Portfolio Performance

### Metrics (2017-10-04 To 2023-08-25)

| Portfolio                | CAGR   | Absolute Returns | Max Drawdown | Calmar Ratio | Sharpe Ratio |
|--------------------------|--------|------------------|--------------|--------------|--------------|
| Market                   | 19.71% | 245%             | -38.45%      | 1.66         | 0.7          |
| Higher correlation       | 21.6%  | 261%             | -35.2%       | 1.9          | 0.72         |
| Lower correlation        | 23.9%  | 285%             | -37.87%      | 2.49         | 0.69         |

### Metrics Before COVID-19 Crash

| Portfolio                | CAGR   | Absolute Returns | Max Drawdown | Calmar Ratio | Sharpe Ratio |
|--------------------------|--------|------------------|--------------|--------------|--------------|
| Market                   | 12.64% | 126%             | -14.47%      | 5.64         | 0.82         |
| Higher correlation       | 13.07% | 127%             | -14.62%      | 5.12         | 0.84         |
| Lower correlation        | 18.02% | 139%             | -14.23%      | 6.04         | 0.77         |

## Variation with Correlation

Portfolios with threshold values of 0.2 and 0.3 exhibit exceptional performance.

| Portfolio                | CAGR   | Absolute Returns | Max Drawdown | Calmar Ratio | Sharpe Ratio |
|--------------------------|--------|------------------|--------------|--------------|--------------|
| 0.2 Portfolio            | 26.6%  | 325%             | -14.6%       | 4.64         | 0.63         |
| 0.3 Portfolio            | 19%    | 275%             | -14.23%      | 2.59         | 0.72         |

## Robust Threshold Values

Threshold values of 0.2 and 0.3 consistently outperform the market across indices (Nifty 100 and Nifty 200).

## Exploring Highly Correlated Portfolios

Highly correlated portfolios can yield surprising results, with the threshold of 0.8 showing strong performance.

| Portfolio                | CAGR   | Absolute Returns | Max Drawdown | Calmar Ratio | Sharpe Ratio |
|--------------------------|--------|------------------|--------------|--------------|--------------|
| 0.6 Portfolio            | 9.6%   | 172%             | -71.63%      | 0.23         | 0.49         |
| 0.7 Portfolio            | 9.09%  | 167%             | -69.05%      | 0.24         | 0.71         |
| 0.8 Portfolio            | 20.5%  | 300%             | -46.44%      | 1.57         | 0.58         |

## Conclusion

Graph theory offers promising avenues for investment analysis in the Indian market. It enables the creation of portfolios with diverse correlations, potentially outperforming the market. Balancing factors such as historical data and stock selection can enhance these models further, making them robust for various market conditions. Mixing stocks with varying correlation strengths can enhance reliability.

*Note: This is a condensed summary of the research report based on the original paper by Joseph Attia, adapted for the Indian market using Nifty 50 as the stock universe.*
