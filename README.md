
**Mutual Fund Portfolio Construction and Optimization Project done using Stacked LSTM**

Collected data from the internet for various mutual fund schemes 
Data taken from AMFI: [https://www.amfiindia.com/net-asset-value/nav-history]

Github link to the csv file: [https://raw.githubusercontent.com/saloniwalimbe/Mutual-Fund-Schemes/main/DailyNAV.csv]

The data is daily 10 year historical Net Asset Values (NAV) for the period of January 1, 2013 to December 31, 2022.

_Project Part I:_
The first part of project includes data cleaning, data exploration and visualisation of different mutual funds.
Each Mutual fund is compared with its respective index performance

_Project Part II:_
Three different portfolios are created based on the performance of each mutual fund.
The portfolios are categorised according to risk -

- Aggressive Risk taker
- Conservative or Risk Averse
- Neutral or Moderately aggressive

The portfolio return, risk and Sharpe ratio is calculated after simulating 10000 portfolios.
Optimised portfolios for each category are
- Aggressive:     Return 12.64%; Risk 10.52%
- Conservative:  Return 7.5%      Risk 3%
- Neutral:          Return 11.24%   Risk 7.3%


_Project Part III:_
Using Stacked LSTM model, forecast for each of the mutual fund schemes has been done for a period of 20 days.
Including the predicted NAV values, portfolio return has been calculated and compared with the earlier optimal portfolio.









