# Stocks-Market-Sim

**Code available upon request**

Stock Market Sim is a Java-based application designed to help users learn and
experiment with stock investments in a virtual environment. It provides tools
to analyze stocks, create portfolios, and simulate investment strategies without
using real money. The program follows a Model-View-Controller (MVC) architecture,
ensuring a clear separation of concerns between data management, user interface,
and application logic.


Features
* Recording of Stock Transactions:
   * Create and manage multiple portfolios containing various stocks.
   * Track over 100 different stock symbols over many years.
   * Stock transactions may be recorded, and the history of the portfolio may be queried to find its value, or its composition at any given time.
   * The program will automatically take into account what days the stock exchange was open, as well as any holidays, and will provide helpful suggestions to assist in correcting invalid dates.
* Stock Analysis:
   * Calculate the gain or loss of a stock over a specified period.
   * Compute the x-day moving average for a stock on a specific date.
   * Identify x-day crossovers for a stock within a specified date range.
* Rebalancing Portfolios:
   * Rebalance a portfolio based on specified target weights for stocks on
     a specific date.
* File saving:
   * Portfolio files may be saved and retrieved from a XML file, as well as imported from previos sessions.
* Performance Over Time:
   * Visualize the performance of a portfolio over a specified time range using a bar chart. The chart will display portfolio value at regular intervals (day, month, or
    year) within the specified range.
   * Scale of the chart will reflect the range of portfolio values,
    ensuring readability and clarity.
## Details
* User Interface:
   * GUI interface (see below)
   * Text-based cli.
* Data Source:
   * Retrieves historical stock data from Alpha Vantage API.
   * Supports a wide range of stock ticker symbols and historical dates.
   * If API calls run out, there is historical data of 3 stocks (AAPL, AMZN, GOOG)
   that come with bundled the project and may be used locally instead.


<div align="center">
  
  <img src="https://github.com/user-attachments/assets/ecf665d2-c1d6-4125-85d5-0fcaf7091334" alt="Home page">
  
  _The home page of the program_
  
  <img src="https://github.com/user-attachments/assets/9b5dda76-adc3-426f-8665-9b652ee66fbd" alt="portfolio screen">

  _The options available for a portfolio_
  
  <img src="https://github.com/user-attachments/assets/11b8b954-0462-4a30-a036-f69e6b985b58" alt="error message">

  _Helpful error messages. The 22nd is suggested since the 24th and the 23rd are weekends_
  
  <img src="https://github.com/user-attachments/assets/dfa2508b-9e8a-4f0f-be7b-4ef20b25a585" alt="portfolio file selection">

  _The menu to import a new porfolio XML file_

  <img width="778" src="https://github.com/user-attachments/assets/da42ff26-e0fa-48c4-8594-2d5e4430a20e" alt="graph making function"> 

  _The graphing function for Tesla stock over one year_
  
</div>

