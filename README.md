# Financial-Analysis
I recently completed a financial data analysis project where I delved into the trends and volatility of six major banks during one of the most turbulent times in financial history. Using Python libraries like Pandas, Seaborn, and Plotly, I analyzed historical stock data from 2006 to 2016 to uncover critical patterns and insights.

#########

My project is an in-depth analysis of stock performance for six major U.S. banks during the years surrounding the 2007–2008 financial crisis and beyond (2006–2016). Here's a breakdown of its components and key elements:

Objective
To analyze financial data and derive insights about stock performance, volatility, and market trends for major banks during a critical period in financial history.

Banks Analyzed
Bank of America (BAC)
Citigroup (C)
Goldman Sachs (GS)
JPMorgan Chase (JPM)
Morgan Stanley (MS)
Wells Fargo (WFC)
Methods & Tools
You utilized Python and its powerful data analysis libraries to perform the following:

Data Collection: Fetched stock data using the yfinance library for accuracy and efficiency.
Data Manipulation: Leveraged pandas to clean and organize stock data into a multi-indexed DataFrame.
Visualization: Used matplotlib, seaborn, and plotly to create insightful visualizations like line plots, heatmaps, and cluster maps.
Statistical Analysis: Calculated returns, standard deviations, and rolling averages to understand trends and volatility.
Key Findings
Stock Peaks:

Citigroup reached the highest closing price of $564.10, while Goldman Sachs and Bank of America hit $247.92 and $54.90, respectively.
Significant Events:

The worst single-day drops for most banks coincided with pivotal moments of the 2008 financial crisis.
Example: January 20, 2009, marked a shared worst drop day for four banks.
Volatility:

Citigroup was the riskiest stock overall, showing the highest standard deviation in returns.
In 2015, Morgan Stanley and Bank of America displayed slightly higher risk compared to others.
Correlations:

Strong correlations were observed between banks' closing prices, reflecting interconnected market movements.
Citigroup's unique volatility stood out.
Market Trends:

Rolling averages and Bollinger Bands revealed periods of high volatility and helped identify long-term trends.
Highlights of the Visualizations
Line Plots: Showed the close price for each bank from 2006 to 2016, making trends and major dips evident.
Pair Plots: Depicted relationships between returns, helping identify outliers and unique behaviors.
Heatmaps: Highlighted correlations among the banks' closing prices, showing how they moved together.
Bollinger Bands: Illustrated price volatility over time for specific banks.
Insights on Methodology
Returns Analysis: You created a new DataFrame to calculate daily percentage changes in closing prices (pct_change()), identifying both gains and losses.
Risk Assessment: Standard deviations of returns quantified volatility, with Citigroup leading overall and specific spikes in 2015 for others.
Visual Storytelling: The combination of traditional plots (line, scatter) with advanced visualizations (heatmap, Bollinger Bands) brought data to life.
Why It Matters
This project exemplifies the use of data-driven approaches to understand financial markets. It also shows how Python's ecosystem can:

Streamline financial analysis.
Provide actionable insights for investors.
Enhance decision-making based on historical data.
