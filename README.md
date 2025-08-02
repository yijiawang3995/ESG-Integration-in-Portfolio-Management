# ESG Integration in Portfolio Management

## For WLRR model:
### 1. `USER.txt` data -- combined dataset from CRSP, COMPUSTAT and I/B/E/S
* Date: 1976 ~ 2020; monthly 
* Variables: 'PERMNO', 'GVKey', 'mcap', 'EP', 'BP', 'CP', 'SP', 'DP', 'FEP1', 'FEP2', 'IBR1', 'IBR2', 'BR1', 'BR2', 'CTEF', 'PM', 'PM71', 'ES', 'ret', 'VOL', 'CRET', 'Ticker', 'STATPERS', 'REP', 'RBP', 'RCP', 'RSP', 'RDP', 'EQ4','EQ8', 'EQ9', 'MQ', 'EQ10', 'USER', 'Cusip', 'smbl', 'date’]

## For Porftolio Construction:
### 1. `KLD.txt` data -- created by KLD Research & Analytics Inc. which became a part of MSCI RiskMetrics Group in the late 2000s (KLD stats ESG rating data)
* Date: 1991 ~ 2016; yearly 
* Variables:

    (1) Company information (Name, Ticker, CUSIP)  

    (2) 7 qualitative issue areas: Community, Corporate Governance, Diversity, Employee Relations, Environment, Human Rights and Product.

    (3) 6 controversial business issues: Alcohol, Gambling, Firearms, Military, Nuclear Power, and Tobacco.
* Meaning:
Summary Counts for each of these 13 areas.
presents a binary summary of positive and negative ESG ratings. 
In each case, if assigned a rating in a particular issue (either positive or negative), this is indicated with a 1 in the corresponding cell.
If the company did not have a strength or concern in that issue, this is indicated with a 0.

### 2. Macroeconomic dataset
* `CPI.csv`: Consumer Price Index for All Urban Consumers: All Items in U.S. City Average from 1990 to 2023.

* `FEDFUNDS.csv`: Effective Federal Funds Rate from 1990 to 2023

* `UNRATE.csv`:Unemployment Rate from 1990 to 2023.

* `F-F_Research_Data_Factors_TXT.zip`: Fama/French 3 Research Factors about SMB, HML and Rm-Rf

### 3. Bechmark dataset - `Rus3000.csv`: Russel 3000 Index Price from 1995 to 2000. (Our bechmark idnex)

