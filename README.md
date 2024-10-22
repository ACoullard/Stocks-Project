# Stocks-Market-Sim

Stock Market Sim is a Java-based application designed to help users learn and
experiment with stock investments in a virtual environment. It provides tools
to analyze stocks, create portfolios, and simulate investment strategies without
using real money. The program follows a Model-View-Controller (MVC) architecture,
ensuring a clear separation of concerns between data management, user interface,
and application logic.

Working Features
* Stock Analysis:
   * Calculate the gain or loss of a stock over a specified period.
   * Compute the x-day moving average for a stock on a specific date.
   * Identify x-day crossovers for a stock within a specified date range.
* Portfolio Management:
   * Create and manage multiple portfolios containing various stocks.
   * Determine the value of a portfolio on a specific date.
* User Interface:
   * Text-based interface for user interaction.
   * Commands for portfolio creation, stock analysis, and value queries.
* Data Source:
   * Retrieves historical stock data from Alpha Vantage API.
   * Supports a wide range of stock ticker symbols and historical dates.
   * Once API Usage runs out, there is historical data of 3 stocks (AAPL, AMZN, GOOG)
   that come with the project that can be run instead.
