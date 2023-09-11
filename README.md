# SDSC2005-Exercise-Time-Series-Analysis-for-Predictive-Research-

Data1: Ex4_data1.xlsx, which contains the following sheets:
•	Intraday_data: the price of HSI per minute from Jan 16, 2023 to Feb 13, 2023 (in total of 18 trading days)
•	Interday_data: the price of HSI per day from Jan 2, 1987 to Feb 10, 2023 (in total of 9,167 trading days of 36 years)
•	Use linear interpolation to fill any empty cell.
Task: 
Identify the following intraday cycles of HSI Price to answer the question that when is the best time of the day to buy (i.e., at the lowest price) and sell (the highest price) stocks on average in HK stock market:
1.	Intraday time: 
a.	Detrend (removing the overall trend of) Price throughout the entire period of the Intraday Data;
b.	Use each 30 minutes of trading time as a half-hourly unit within each trading day; 
c.	Use 1-hot encoding to create the half-hourly variables;
d.	Use an OLS regression with Price as the DV and hourly variables as the IVs to measure the effect of “half-hour of the day” on Price;
e.	Optional: use alternative way(s) to measure the best time to buy/sell based on OLS regression. 
2.	Interday time:
a.	Detrend Price throughout the entire period of the Interday Data;
b.	Use each trading day as a daily unit within each trading week and each month as a monthly unit within each month, respectively;
c.	Use 1-hot encoding to create the daily and monthly variable(s), respectively;
d.	Use an OLS regression with Price as the DV and daily and monthly variables as the IVs to measure the effect of “day of the week” and “month of the year” on Price, respectively;
e.	Optional: use alternative way(s) to create best day/month to buy/sell on the OLS regression report the resulting effect if significantly greater than the 1-hot encoding approach (grading policy: extra point(s) for significantly improved results, depending on the size of the improvement; no penalty for wrong answers).
