# Data Analysis for Bitcoin and Ethereum from 2014 to 2024

This data analysis was done using the dataset from Kaggle: [bitcoin_ethereum-2014-2024](https://www.kaggle.com/datasets/kapturovalexander/bitcoin-and-ethereum-prices-from-start-to-2023)


## General Description about the data set: 

The dataset contains the information about __Daily__ prices for Bitcoin (BTC) and Ethereum (ETH) from differente range of dates but it is basically from January 2014 to May 2024

### About the .csv files:

The dataset was originally spread in 6 different files 2 of them with the __MarketCap__ for Bitcoin and Ethereum.
The other 4 are 2 for the daily prices for Bitcion and Ethereum with their prices __compared to USD__

This is why I decided to join the files __"Bitcoin USD (01-05.2024)"__ and __"BTC-USD (2014-2024)"__, and the __"ETH-USD (01-05.2024)"__ with __"ETH-USD (2017-2024)"__ in order to create only 2 files, one for BTC and other for ETH making the analysis easier. 


## Initial investigation:

Used methods like: `.head()`, `tail()`, `info()`, `describe()`, `isnull().sum()` and `duplicated().sum()` in order to have a better understanding for each CSV file.