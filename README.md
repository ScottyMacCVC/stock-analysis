# Actively Traded Stock Correlation to Return %

## We will explore the correlation between the daily volume of a stock and the % return.

### Our current process will look at 2017 & 2018 stock volume & return. We can extrapolate from the past whether there is, in fact, a correlation between the two measurements. 

## Analysis and Challenges 

### 2017 fails to correlate stock volume & return. The largest volume, SPWR, produced a 23.1% return and the highest % return was DQ with 199.4%. But the issue is DQ has the lowest total daily volume in the set. Effectively, DQ proves the theory incorrect and we cannot correlate return % to total daily volume in 2017. 

### ![VBA_Challenge_2017](https://github.com/ScottyMacCVC/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png) 

### 2018 fails to correlate stock volume & return. When you look at the two successful tickers, ENPH & RUN, there is some correlation between volume & return. ENPH hit 607,473,500 with 81.9% return and RUN hit 502,757,100 with 84.0% return. The challenge is a different stock, SPWR, has 538,024,300 daily volume, which is more than RUN but SPWR received -44.6% return. If we were to use the daily volume theory here, we would be left holding the bill for the losses on SPWR. We can say the same about FSLR. It would be a mistake to rely on Total Daily Volume as the key performance indicatior in 2018, therefore proving our theory incorrect again. 

### ![VBA_Challenge_2018](https://github.com/ScottyMacCVC/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)

## Results

- **Advantages and Disadvantages of the Refactored Code**
-- The advantage is in the speed of the reporting. It is infuriating to wait for a slow processor and is more impactful if the process is used often. We want to design our code to handle the workload. reforge past work to include best practices. A code may be built for a specific event and may not include, or needed to include, a larger data set. Data sets are growing as more devices collect data and old code will likely need updating. The disadvantage is we may screw up a working code, impacting the team, and causing pure chaos. Hopefully the original code is saved somewhere, because if the update happened to the master code then the team is picking through the lines. 

- **Advantages and Disadvantages of the Original Code**
-- The single most important advantage is the code is working. Although we can improve on a code, we must carefully work the changes into the system. The effects of pushing a bad code can take years and tears to undo. The disadvantage is keeping up with current systems. We are building on top of old code. If the older code does not allow new operations, size of data set, or takes too long to run the added lines, the code will impede the companies ability to grow. 
---
### Please see Hyperlink for our referenced XL sheet  - [VBA_Challenge.xlsx](https://github.com/ScottyMacCVC/stock-analysis/blob/main/green_stocks.xlsm)
---
