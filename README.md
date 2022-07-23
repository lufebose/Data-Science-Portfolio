# R-Data-Science-Portfolio

Welcome to my GitHub. Here you will find my Portfolio. 

Includes the major Data Science projects that I've created using R Studio 


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

![](/images/Filtered%20data.png)

