# SP-Arbitrage - Is there an opportunity?

# ***Project Topic/Title***

Evaluate the relative change of S&P 500 futures (front ES and MES contract) and SPY ETF over a period of 4 years. This will include significant market events. <br>
How strong of a correlation will we find? Do different time periods matter? <br>

# ***Introduction:***

Intrigued by the launch of the micro e-mini contracts for major indices by the CME on May 6, 2019, we chose to delve further into the market's adoption of the new indices.  Noting that the new contracts allow market participants to gain exposure to price fluctuations in the S&P 500, Russell, Dow Jones 30, and Nasdaq indices at minimal costs than the existing e-minis, we sought to demonstrate that the price movements across the three S&P500 futures indices were highly correlated such that an arbitrage opportunity did not exist during the burst of uncertainty.  At the core of our analysis, we focused on the possibility of arbitrage over four years that registered a few seismic events, including but not limited to a global pandemic (COVID), elections resulting from uncertainty in the US, Russia's evasion of Ukraine, and a global inflationary environment caused by global supply-chain disruptions and a reduction oil production capacity by OPEC during the early days in the Pandemic.<br>


# ***Definitions and Description:***

Futures Contract:<br>
Derivative financial contracts that obligate parties to buy or sell an asset at a predetermined future date and price.<br>

Exchange Traded Fund (ETF):
ETFs or "exchange-traded funds" are exactly as the name implies: funds that trade on exchanges, generally tracking a specific index. When you invest in an ETF, you get a bundle of assets you can buy and sell during market hours.<br>

E-Mini (ES) S&P 500 Futures Contract: <br>
The E-mini S&P 500 futures contract tracks the S&P 500 Index. It trades on the Chicago Mercantile Exchange (CME) under the ticker symbol ES. The contract tracks the stock prices of the largest U.S. companies listed on the S&P 500 Index. Investors can use contracts as a way to hedge or speculate on the future of the S&P 500 Index. The E-mini S&P 500 futures contract is $50 x the S&P 500 Index and has a minimum tick of .25 index points. This translates to $50 per single point change and $12.50 per tick.<br>

Micro E-mini (MES) S&P 500 Futures Contract: <br>
Micro E-mini S&P 500 futures (MES) offer smaller-sized versions of the Chicago Mercantile Exchange's (CME) liquid benchmark E-mini contracts.
They are designed to manage exposure to the 500 U.S. large-cap stocks tracked by the S&P 500 Index, widely regarded as the best single gauge of the U.S. stock market. The Micro E-mini S&P 500 futures contract is $5 x the S&P 500 Index and has a minimum tick of 0.25 index points. This translates to $5 per single point change and $1.25 per tick.<br>

SPY ETF: <br>
The SPDR S&P 500 ETF Trust (SPY) is one of the most popular Exchange Traded Funds. It aims to track the Standard & Poor’s (S&P) 500 Index, which comprises 500 large-cap U.S. stocks. These stocks are selected by a committee based on market size, liquidity, and industry. The S&P 500 serves as one of the main benchmarks of the U.S. equity market and indicates the financial health and stability of the economy. Also known as the SPY ETF, the fund was established in January 1993. <br>

WTI Futures Contract: <br>
WTI stands for West Texas Intermediate (occasionally called Texas Light Sweet), an oil benchmark that is central to commodities trading. It is one of the three major oil benchmarks used in trading, the others being Brent crude and Dubai/Oman. The volatility of crude oil prices after the US oil price decontrol led to the development of the NYMEX WTI Light Sweet Crude Oil futures contract in 1983. The NYMEX Crude Oil contract trades under the symbol CL on the New York Mercantile Exchange, now part of Chicago Mercantile Exchange. The contract is for 1,000 US barrels, or 42,000 US gallons, of WTI crude oil, the minimum tick size of the contract is $0.01 per barrel ($10 for contract), and the contract price is quoted in US dollars. Monthly contracts are available for the current year, the following 10 calendar years, and 2 additional months. <br>

Financial Metrics Analyzed: Monte Carlo, relative price/correlation, annual return, sharpe ratio, other financial metrics <br>

Date Range of all data sets: May 2019 - May 2023 <br>

Economic Events & News: (TO BE FURTHER DEFINED) GDP data, Employment, Fed Interest Rates  <br>

# ***Tools for Analysis:***

Alpaca API data <br>
Correlation Matrices <br>
HVPlot: Visualize relative profiles <br>
Monte Carlo Simulation <br>
Pandas: data cleaning/calculating returns <br>


# ***Team Members***
Susan Bengo  <br>
Michael Cody <br>
TJ Wentling <br>
Tingjun Yang <br>
