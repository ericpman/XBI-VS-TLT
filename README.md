# XBI-VS-TLT

### This project explores the relationship between the TLT and the XBI. Our thesis for the relationship between these two ETFs relies on the observation that the companies within the XBI smaller biotech companies, and rely heavy on borrowing capital to fund their expenditures. Therefore, these companies are highly interest rate sensitive.

The TLT is an ETF which tracks the 20 Year US Treasuries. The price of TLT is reflective of interest rates. As interest rates go down, the TLT will go up. Conversely, as interest rates rise, the TLT will go down. This is due to the inverse relationship between bonds and interest rates. This project looks at exploring the relationship between the biotechnology sector and the TLT. As the TLT reacts to movement in interest rates, the stocks within the XBI should move as well. As interest rates go up, the TLT will move down, and so too should the XBI according to our thesis. Just as well, should interest rates down down, the TLT will move up and so too should the XBI. 

Our code uses pandas, numpy, matplotlib, and yfinance libraries to achieve our objectives. The data for TLT and XBI are files in csv format. The data for SPY is derived using yfinance. SPY is used for comparison purposes only, to show the performance of our strategy against the SP500 returns.

There are 4 outputs of data crucial to understanding our results.
1) The total performance of the XBI Open to Close when TLT is positive overnight. This is calculated by taking the sum of all our returns for those days and expressing it as a percentage of returns. Included is data from 2012 - Present.
2) A line chart showing the Cumulative performance of XBI Open to Close when TLT is positive overnight. Most notably in this data here, we can see extreme outperformance in this strategy during the 2022 - 2023 year, when interest rates were rising fast.
3) A comparison between the average return of the XBI Open to Close when the TLT is positive overnight, and the average return of XBI when the TLT is positive overnight MORE THAN 0.5%
4) A final comparison between the 20222-2023 average return of the XBI Open to Close when TLT is positive overnight, average return of XBI Open to Close when TLT is positive more than 0.5% overnight, and the average return of SPY for this enitre time period. We are honing in on this specific time period because this is when we had a large rise in interest rates, making the market more sensitive to interest rates. 
