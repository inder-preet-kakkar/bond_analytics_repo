# Electoral Bond Dataset

In February 2024, the Supreme Court (SC) of India ordered State Bank of India (SBI) to release the data on Electoral Bonds between 2019 and 2024. The dataset was released to the Election Commission of India (ECI) which then made it public on its website on 21 March, 2024.

The data was released as two pdf files one with a list of bond buyers and the other with the political parties which cashed these bonds. For this repo those pdfs have been converted to csv files so that people have easy access to the dataset in a format that can be quickly analysed using data science tools. 

### Description of data files

1. `bond_buyers.csv`
This file contains information about the bonds that were bought with following columns:
   - Reference No  (URN)
   - Journal Date
   - Date of Purchase
   - Date of Expiry
   - Name of the Purchaser
   - Prefix
   - Bond Number 
   - Denominations
   - Issue Branch Code
   - Issue Teller
   - Status

2. `bond_recipients.csv`
This file contains information about the bonds that were cashed by the political parties with following columns:
   - Date of Encashment
   - Name of the Political Party
   - Account no. of Political Party
   - Prefix
   - Bond Number
   - Denominations
   - Pay Branch Code
   - Pay Teller

### How to get started with analysing this data
The data released by the ECI did not have any descriptions of the column names. Some of them are axiomatic but some of them are misleading as well. I have hastily put together a notebook 
```exploratory_data_analytics.ipynb``` in the `notebooks` folder ot help one get started parsing these files and investigate the dataset.