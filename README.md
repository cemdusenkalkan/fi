# fi

a project where I collect all of my quantitative finance & algorithmic trading knowledge together and work,
collect the codes up, reviewing the projects, managing it, upgrading, saving and leaving milestones in the way for others,
friends, and for future me.

Mindmap:

![map](https://i.imgur.com/IsAUdUe.png)

First, I wanted to step on volatility & momentum seeking and maybe training a model about it.

## Volatility & Momentum Based Model

![map](https://imgur.com/1TOqzrr.png)

### Overview of the model:
Objective:
The primary objective of this model is to identify periods of increased volatility and significant momentum in financial markets, particularly when they indicate the initiation of a price trend. This model focuses on utilizing key indicators, specifically volume, rate of change (ROC), and on-balance volume (OBV), to make informed assessments of market conditions.

Key Components:

Volume: Volume, representing the number of assets traded during a specific time period, serves as a crucial input for assessing market activity. Unusual spikes in volume often precede significant price movements, and this metric will play a central role in the model's analysis.

Rate of Change (ROC): ROC calculates the percentage change in asset prices over a specified time frame. It helps in identifying rapid price changes, which can be indicative of momentum shifts in the market.

On-Balance Volume (OBV): OBV is a volume-based indicator that tracks the cumulative volume flow in and out of an asset. It is utilized to gauge the strength of trends and identify potential trend reversals.

Machine Learning Approach:
The model employs machine learning techniques to automate the process of seeking substantial market moves. Although specific details regarding LSTM (Long Short-Term Memory) and GARCH (Generalized Autoregressive Conditional Heteroskedasticity) models are not provided due to limited familiarity, the overarching goal is to educate a machine learning model. This model aims to detect significant market movements that may lead to potential trading opportunities.

Model Output:
The output of the model will be alerts or signals generated when it detects conditions suggestive of noteworthy volatility or momentum in the market. These alerts will serve as indications for further investigation or potential trading actions.

Implementation Considerations:
Given the potential complexity of LSTM and GARCH models, the initial implementation may involve simpler machine learning algorithms and statistical techniques. The model will continuously evolve as the user's knowledge and expertise in these advanced models grow.

### Purpose and objectives: 
The main goal of this strategy is to use data and computational algorithms to find prospective profit-making opportunities in financial markets. Traders and investors can be better informed about possible price changes and alter their strategies by spotting moments of high volatility and momentum.

### Expected outcomes and benefits:
Improved Accuracy: The model intends to deliver a more accurate evaluation of market conditions by combining both traditional indicators and machine learning.
Adaptability: The model's approach to continual learning ensures that it stays relevant even as market dynamics change.
Efficiency: By automating the process of spotting major market moves, time is saved and the possibility of human mistake is reduced.

### Data collection tools and platforms:

APIs:
Binance API: Offers real-time trading data, including volume, prices, and historical data.
CoinGecko: Another reliable source for cryptocurrency data.
Yahoo Fi: Another reliable source for financial data.
Cleaning: Removing any outliers or erroneous data.
Frequency: Depending on the trading strategy, we might opt for 15-min, hourly, or daily data. For higher-frequency trading, even 5-minute data could be useful.

### Types of models: For now, I really don't know.

### Training process:

### Visualizing model predictions and actual outcomes:

### Comparative analysis of different model results:
