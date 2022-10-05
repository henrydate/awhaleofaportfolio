# A Whale of a Portfolio
<br>
We have created a Financial Investment Analyser.  This tool analyses a number of risk scenarios to create a considered investment portfolio dependent on a number of client variables.   <br>
<br>
We have drawn down our Finance data using the yFinance API.   <br>
<br>
We have selected a a set of 10 tickers based on our own project risk analysis and assigned them as 
'high growth' or 'low vol'.  Stocks are as follows:  <br>
<br>

    high growth:  AAPL, TSLA, NKE, AMZN, WMT  <br>
    low vol: LDOS, INCY, NBIX, KO, AIZ  <br>
<br>


Client variables are:  <br>
    - age  <br>
    - years to retirement  <br>
    - the number of years they would like to invest for <br>
    - investment comfort level, levels are as follows:  <br>

1. I do not want to lose my money, I would rather have a low return than risk the loss of any part of my capital.  <br>
2. I prefer an amount of stablity, watching the market fluctuate makes me feel sick.  <br>
3. I can accept a degree of market fluctation to achieve better results  <br>
4. I am willing to accept moderate market fluctuations to achieve better returns.  <br>
5. To receive the maximum return on my investment, I am willing to accept a higher investmemt fluctuations and a high degree of risk.  <br>
--    Note: Option 1 is a stable investment strategy, and 5 has the highest risk, with the potential for higher returns.)  <br>
<br>
Once we have this information we assign stock weights based on client's risk appetite.  <br>
<br>
The output below is an example of the share investment weights for the client's seletced risk level appetite.  <br>

![](riskweighted.png)









    
