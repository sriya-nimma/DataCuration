# DataCuration

Project Goal: To collect data through webscraping and creating meaningful data visualizations. 

API/Libraries: Used BeautifulSoup, Pandas, Matplotlib, requests

Data: From YahooFinance webpage (open source)
License: MIT License

Data Dictionary:

Symbol:

-String
- The unique company symbol
  
 Name:

- String
- The full name of the company
  
Price:

- Float
- The current price of the stock
  
Change:

- Float
- The change in the stock's price compared to the last period
  
% Change:

- Float
- The percentage change in the stock's price compared to the last period

Potential Bias: Yahoo Finance gets constantly updated from outside sources so there could be possibility of innacurate data or bias depeneding on where the data is coming from.
