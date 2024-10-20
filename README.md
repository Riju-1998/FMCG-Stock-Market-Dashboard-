# FMCG-Stock-Market-Dashboard-
FMCG Stock Market Dashboard 

This project is a comprehensive stock market dashboard developed in Power BI (or Excel), which analyzes the FMCG Index and provides interactive visualizations for stock price trends, volatility, daily returns, and other statistical measures.

📂 Overview
The dashboard offers insights into the FMCG stock index's performance, allowing users to:

Track stock price movements over time.
Analyze daily returns and volatility.
Compare the FMCG index with other market indices like SENSEX or NIFTY.
Visualize statistical measures such as mean, median, and mode of stock prices.
Understand correlation with other indices.
Analyze risk-reward using scatter plots and statistical indicators.
📈 Dashboard Visualizations
The dashboard provides multiple charts and visualizations to analyze the stock data effectively:

1. Trend Analysis: Line Chart for Closing Prices
Purpose: Shows the trend of the FMCG index over time (rising or falling).
Data: X-axis: Date, Y-axis: Closing Prices.
Enhancement: Added Moving Average (e.g., 5-day or 10-day) to smooth out short-term fluctuations.
2. Volatility Analysis: Bar Chart for Daily Returns
Purpose: Visualize the daily changes in stock price to assess volatility.
Data: Calculated Daily Returns using the formula:
excel

Daily Return = (Today's Close - Yesterday's Close) / Yesterday's Close
Enhancement: Color-coded bars (green for positive returns, red for negative returns).
3. High-Low Price Spread: Area/Line Chart
Purpose: Visualize the spread between the daily high and low prices, indicating volatility for the day.
Data: (High - Low) column.
Enhancement: Highlighted days with high volatility using conditional coloring.
4. Candlestick Chart: Stock Candlestick Chart
Purpose: Show stock movement within a day (open, high, low, close).
Data: Columns for Open, High, Low, and Close.
Enhancement: Included markers for significant trends or reversal points.
5. Correlation Analysis: Scatter Plot for FMCG Index vs. SENSEX/NIFTY
Purpose: Analyze the correlation between the FMCG index and other relevant indices (e.g., SENSEX, NIFTY).
Data: FMCG closing prices on one axis and SENSEX/NIFTY prices on the other.
6. Risk-Reward Analysis: Risk-Return Scatter Plot
Purpose: Display risk levels (volatility) vs. returns for different periods.
Data: Plotted daily returns against standard deviation.
Enhancement: Color-coded based on the return-to-risk ratio.
7. Statistical Measures: Summary Table and Histogram
Purpose: Display basic statistical measures like mean, median, and mode for closing prices.
Data: Columns from the price data (Open, Close, High, Low).
Histogram: Visualizes the distribution of daily returns to show data spread.
🧮 Calculations and KPIs
Volatility (Standard Deviation of Returns):

Formula: STDEV.P(Returns)
Purpose: Quantifies how much prices fluctuate over time.
Example Result: 0.0030 (or 0.30%)
Maximum Daily High-Low Range:

Formula: MAX(High - Low)
Example Result: 338.13
Maximum/Minimum Daily Returns:

Formula for Daily Return:
excel

Daily Return = (Today’s Close - Yesterday’s Close) / Yesterday’s Close
Example Results: Maximum: -0.0039 (or -0.39%), Minimum: -0.0122 (or -1.22%)
🎛️ Interactive Features
Slicers:
To enhance interactivity and enable users to filter and explore specific data, slicers have been added to the dashboard:

Date Slicer: Filter by specific date ranges.
Time Period Slicer: Daily, weekly, or monthly view of the data.
Price Slicers: Open, Close, High, Low price ranges.
Volatility Slicer: Filter based on high/low price spreads.
Daily Returns Slicer: Focus on positive or negative returns.
📊 Sample Data
Here is a snippet of the data used in the dashboard:

Date	Open	High	Low	Close	High-Low	Open-Close
01-01-2024	20507.21	20651.56	20456.08	20567.06	195.48	-59.85
29-12-2023	20342.30	20487.66	20288.98	20467.98	198.68	-125.68
28-12-2023	20092.59	20317.48	20059.18	20292.76	258.30	-200.17
27-12-2023	20016.43	20072.04	19957.22	20044.26	114.82	-27.83
26-12-2023	19918.82	19991.86	19884.04	19965.92	107.82	-47.10
🔧 Tools Used
Power BI for creating dynamic and interactive visualizations.
Excel for data preprocessing and calculations.
DAX functions for calculating key metrics (e.g., Daily Returns, Volatility).
GitHub to showcase the code and project details.
🚀 How to Use This Dashboard
Download the Power BI file from the repository.
Open the file in Power BI and connect it to the sample data (included in the repository).
Use slicers to filter the data based on different criteria (date, price range, returns).
Explore the various visualizations to gain insights into the FMCG stock performance.
📎 Repository Files
Dashboard.pbix: Power BI file containing the full dashboard.
FMCG_Data.xlsx: Sample stock price data used in the analysis.
README.md: This documentation file.
📝 License
This project is open-source and available for anyone to use or contribute to. Feel free to modify and enhance the dashboard for your use case.

Example Code Snippet for Daily Returns Calculation in Excel:
excel

= (B2 - A2) / A2
🌟 Conclusion
This dashboard provides comprehensive insights into the FMCG index using interactive charts and statistical analysis. With volatility measures, daily return analysis, and slicers for dynamic filtering, the dashboard enables users to explore market trends, performance, and correlations effectively.


