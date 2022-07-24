# R-Data-Science-Portfolio

Welcome to my GitHub. My name is Luis Felipe Bolaños. I'm an economist graduated from the University of Costa Rica in 2020 and currently I'm coursing my MSc in Nova School of Business and Economics in Lisbon, Portugal. 

Here you will find my Portfolio. It includes the major Data Science projects that I've created using R Studio 


## Project 1: Analyzing Bitcoin (BTC) price while inflation expectations are high

i. Used tidyquant, tidyverse, timetk, lubridate, dplyr ggplot2 to extract, analyze and visualize how BTC has behaved during 2022 when it went below $20,000 

ii. Obtained other time series such as University of Michigan monthly Inflation Expectations from the FRED Website using Tidyquant in order to better understand BTC's downward spiral

iii. Analyzed the bond and foreign exchange market by extracting information in an automated way using the Tidyquant Package in R

![](/images/btc_price.png)

![](/images/infl_exp.png)

![](/images/dollar2022.png)



## Project 2: Forecasting the Costa Rican Colon (CRC) Exchange Rate using the Prophet Package and Time Series filtering using mFilter


i. Used the Prophet package to forecast the CRC/USD exchange rate. Prophet proved to be a good package to forecast these kinds of series because of non-linearity and high seasonality

ii. With Prophet the seasonality of the variables was analyzed thoroughly. It was observed that the days with the highest seasonality are from Wednesday to Saturday whereas the months with the highest seasonality are June and November

iii. mFilter was used to separate the different components of the time series

![](/images/forecasting365.png)

![](/images/trend-weekly-yearly.png)

![](/images/filtered_data.png)

## Project 3: Analyzing commodities when volatility is high and bond & equity returns are low using the tidyquant Package

i. Analyzed the what has happened with the price of commodities and how these real assets have been one of the best options to take refuge against inflation in 2022 

ii. Obtained the VIX index data using tidyquant in order to understand what has happened with volatility and why commodities are still a risky choice to invest nowadays. 

![](images/Commodities_july_2022.png)

![](images/vix_index.png)

