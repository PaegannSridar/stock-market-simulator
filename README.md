# stock-market-simulator

This is my first project to learn to use GitHub. 
I am using one of my favourite topic, finance & stock markets.

### The simulator strategy:

**To buy the stocks:**

The simulator calculates the short-term moving average (50 days) and the long-term moving average (150 days).
The average logarithmic price change over the past week is also calculated.

If the short-term moving average is greater than the long-term moving average then the stock is bought. Also, if the average price change is more than 1% in the past week then the stock is bought.


**To sell the stocks:**

The stocks are bought if the short-term moving average is less than the long-term moving average. 
Also, if the stock price falls by 2% or gains 4%, the stock is bought.


[Stock performance](../../../../../../private/var/folders/l0/q58b2snx1m50wmj_3lblgckm0000gn/T/clipboard1.png)