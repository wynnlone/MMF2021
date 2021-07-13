# MMF2021
# RM Lab

# Folder: input_data ========================================
# All the data collected externally

## Market price data:

## Barclay Fund of Funds Index, used as Benchmark
## Since they are so varied, funds of funds can be hard to track as a group and to compare. However, an index does exist. The Barclay Fund of Funds Index, sponsored by Barclay-Hedge, a provider of data on alternative investments, is a measure of the average return of all FOFs that report into the company database; it includes some 500 to 650 funds.


### from yahoofinance:

#### USD 

#### 1. Equity & Credit

#### SPY: SPDR S&P 500 Trust ETF
#### is one of the most popular funds that aims to track the Standard & Poor's 500 Index.
#### this eft represents the large- and mid-cap U.S. stocks.

#### QQQ: Invesco QQQ Trust ETF
#### is an exchange-traded fund that tracks the Nasdaq-100 Index.
#### this eft represents the 100 largest non-financial companies listed on the Nasdaq based on market cap..

#### VWO: Vanguard FTSE Emerging Markets Index Fund ETF
#### tracks the return of the FTSE Emerging Markets All Cap China A Inclusion Index.
#### this eft represents stocks of companies located in emerging markets around the world, such as China, Brazil, Taiwan, and South Africa.

#### EWC: iShares MSCI Canada ETF
#### tracks the investment results of an index composed of Canadian equities.
#### this eft represents large and mid-sized companies in Canada.

#### EFA: iShares MSCI EAFE ETF
#### track the investment results of an index composed of large- and mid-capitalization developed market equities, excluding the U.S. and Canada.
#### this etf represents a broad range of companies in Europe, Australia, Asia, and the Far East.

#### VGK: Vanguard FTSE Europe Index Fund ETF Shares
#### tracks the performance of the FTSE Developed Europe All Cap Index, which measures the investment return of stocks issued by companies located in the major markets of Europe.
#### this etf represents stocks of companies located in Austria, Belgium, Denmark, Finland, France, Germany, Greece, Ireland, Italy,  the Netherlands, Norway, Portugal, Spain, Sweden, Switzerland, and the United Kingdom.

#### IOO: iShares Global 100 ETF 
#### tracks the investment results of an index composed of 100 large-capitalization global equities.
#### this etf represents a broad range of large international companies in developed and emerging markets.

#### LQD: iShares iBoxx $ Investment Grade Corporate Bond ETF (did not include)
#### tracks the investment results of an index composed of U.S. dollar-denominated, investment grade corporate bonds. 

#### 2. Governmet Bond
#### SHY: iShares 1-3 Year Treasury Bond ETF
#### tracks the investment results of an index composed of U.S. Treasury bonds with remaining maturities between one and three years.
#### this eft represents short-term U.S. Treasury bonds.

#### IEF: iShares 7-10 Year Treasury Bond ETF
#### tracks the investment results of an index composed of U.S. Treasury bonds with remaining maturities between seven and ten years.
#### this eft represents intermediate-term U.S. Treasury bonds.

#### 3. Inflation Bond
#### TIP: iShares TIPS Bond ETF
#### tracks the investment results of an index composed of inflation-protected U.S. Treasury bonds.
#### this eft represents government bonds whose face value rises with inflation.

#### 4. Real Estate / Commodity
#### IYR: iShares U.S. Real Estate ETF
#### tracks the investment results of an index composed of U.S. equities in the real estate sector.
#### this eft represents U.S. real estate companies and REITs, which invest in real estate directly and trade like stocks.

#### DBC: Invesco DB Commodity Index Tracking Fund (did not include)
#### tracks changes, whether positive or negative, in the level of the DBIQ Optimum Yield Diversified Commodity Index Excess Return™ (DBIQ Opt Yield Diversified Comm Index ER or Index) plus the interest income from the Fund's holdings of primarily US Treasury securities and money market income less the Fund's expenses.
#### this etf represents 14 of the most heavily traded and important physical commodities in the world.

### CAD 
### ref: https://en.wikipedia.org/wiki/List_of_Canadian_exchange-traded_funds#ETF_Table

#### 1. Equity & Credit

#### XSP.TO: iShares Core SP 500 Index
#### tracks the investment results of an index composed of large-capitalization U.S. equities.
#### this etf represents large, established U.S. companies.

#### XIU.TO：iShares S&P/TSX 60 Index ETF
#### tracks the performance of the S&P/TSX 60 Index, net of expenses.
#### this etf represents large, established Canadian companies.

#### XIN.TO: iShares MSCI EAFE Index 
#### track the investment results of an index composed of large- and mid-capitalization developed market equities, excluding the U.S. and Canada.
#### this etf represents a broad range of companies in Europe, Australia, Asia, and the Far East.

#### XBB.TO: Shares Core Canadian Universe Bond Index ETF
#### tracks the performance of the FTSE Canada Universe Bond Index, net of expenses.
#### this eft represents the Canadian investment grade bond market.

#### 2. Governmet Bond

#### XGB.TO: iShares Canadian Government Bond Index ETF
#### tracks the performance of the FTSE Canada All Government Bond Index™, net of expenses.
#### this eft represents Canadian investment grade government bonds with maturities of at least 1 year.

#### 3. Inflation Bond

#### XRB.TO: iShares Canadian Real Return Bond Index ETF
#### tracks the performance of the FTSE Canada Real Return Bond Index™, net of expenses.
#### this eft represents Canadian federal and provincial real return bonds.

#### 4. Real Estate / Commodity

#### XRE.TO: iShares S&P/TSX Capped REIT Index ETF
#### tracks the performance of the S&P/TSX Capped REIT Index, net of expenses..
#### this eft represents different types of Canadian Real Estate Income Trusts (REITs) in a single fund, such as the retail, residential, office and industrial.


## MarcoEconomic data:
## From statistic canada, FED, OECD database

### U.S.

#### U.S. Fed funds
#### U.S. CPI
#### U.S. GDP
#### U.S. Unemployment rate

### Canada

#### CANADA Interest rate
#### CANADA CPI
#### CANADA GDP

#### FX CAD/USD

## Factor data:

### Fama-French factors

#### Rm-Rf: the difference between the return on the value-weight (VW) market portfolio and risk-free rate.
#### SMB: the return on a diversified portfolio of small stocks minus the return on a diversified portfolio of big stocks.
#### HML: the difference between the returns on diversified portfolios of high and low B/M stocks.
#### RMW: the difference between the returns on diversified portfolios of stocks with robust and weak profitability
#### CMA: the difference between the returns on diversified portfolios of low and high investment stocks (conservative and aggressive).

# Folder: performance_data ===================================================
# Time 2011-2016
# Test result generated using different strategies

## EW: Equal Weighted
## AW: All Weather
## MV: Minimum Variance
## MS: Maxium Sharpe Ratio
## NR: Naive Risk Parity
## RP: Risk Parity
## TF: Trend Following
## TR: Trend Reversal

## each strategy inculdes two accounts, usd and cad. inculdes Price time series data and return data. 


# Folder: report_data ===================================================
# Time 2016-2021
# result from selected strategy

## AW is selected. 
## include price and return information of portfolio.
## some other info such as weight, transaction record, fees, unit of shares holding histry also included.


# Folder: code ===================================
# Contains all the code

## Optimize:
## Strategy builder. This is the process of taking processed data and use investment strategy to optimize the portfolio and achieve weight of each asset.
## (has been intergrated with Main)

## Main:
## is the main file for training, validation and testing.
## Process include calibration, asset allocation, rebalancing, fee calculation, performance time series and some risk metric calculation.
## takes input data and output performance data and report data

## Risk Analysis - VaR - Draft
## is the draft template for historical VaR and Stress VaR
## will need to be modified and polished once the data files and allocation functions are done.


# Folder: analysis ====================================
# contains all the analysis of report data

## Analysis_sharpe11-16.xlsw analyzes the portoflio perfromance of 7 different strategies including AW, EW, MV, NR, RP, MS, TF from 2011-04-01 to 2016-04-01.
## ecodata_analysis.xlsw analyzes the relationship between economic data.



# Folder: template_reference ==========================
# for our own reference


#






