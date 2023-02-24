# Top5_Stocks_of_NASDAQ_Prediction
**Goal: Predicting the price of the Nasdaq 100 index and top 5 stocks 55 days later by PyTorch Deep Learning Model**

- **Index**: NASDAQ 100
- **Stocks**: Apple, Microsoft, Alphabet, Amazon, Meta
- **US Economic Data**: US Consumer Price Index Yearly and US Interest Rate

## Product Vision

The goal of this project is to develop a predictive model that can accurately predict the price of the Nasdaq 100 index and top 5 stocks 55 days later. The scope of the project includes collecting data from eight different datasets, preprocessing the data, developing three models using PyTorch, and deploying the models to a demo application. The success metrics for the project include achieving a high level of accuracy in predicting the stock prices and user satisfaction with the demo application's functionality.

The predictive model should be able to handle large amounts of data, identify trends and patterns in the data, and use this information to make accurate predictions of the stock prices. The model should be flexible and adaptable to changes in market conditions, and it should be able to provide real-time predictions of the stock prices.

The demo application should be user-friendly and easy to navigate, with an intuitive interface that allows users to input parameters and obtain predictions in real-time. The application should provide visualizations of the predicted stock prices, as well as key technical indicators that are used in the model.

Overall, the product should provide a valuable tool for investors, traders, and financial analysts who are looking for a reliable and accurate way to predict the stock prices of the Nasdaq 100 index and top 5 stocks.

![image](https://user-images.githubusercontent.com/113067787/221213135-e7f8b0ab-7004-445e-9453-9b3c1905624e.png)

## Project Roadmap
1. Data Collection
    - Source of Data
    - Import Libraries
    - Import Datasets
2. Data Preprocessing
    - Features Preprocessing
    - Merge Datasets
3. Exploratory Data Analysis
    - Data Visualization For Understanding Data
    - Correlation Between Stocks and Index
    - Create New Features (Technical Analysis)
    - Visualization of New Features
4. Model Development
    - Preparation Train & Test Sets
    - PyTorch Model #1
    - PyTorch Model #2
    - PyTorch Model #3
    - Optimization
5. Model Deployment
    - Final Model
    - Demo Testing
    
## Source of Data						

TimeFrame(2015.01.01 - 2023.02.16)

Nasdaq 100 (NDX) 		https://www.investing.com/indices/nq-100-historical-data

The Nasdaq-100 is a stock market index made up of 101 equity securities issued by 100 of the largest non-financial companies listed on the Nasdaq stock exchange. It is a modified capitalization-weighted index. (Wikipedia)

•	Date
•	Price: Last price during a trading session
•	Open: Open price for a trading session
•	High: Highest price during trading session
•	Low: Lowest price during trading session
•	Vol: Trading volume
•	Change%: Daily Change

- Apple (AAPL) 			https://www.investing.com/equities/apple-computer-inc
- Microsoft (MSFT) 		https://www.investing.com/equities/microsoft-corp
- Alphabet C (GOOG) 		https://www.investing.com/equities/google-inc-c
- Amazon.com (AMZN) 	https://www.investing.com/equities/amazon-com-inc
- Meta Platforms (META) 	https://www.investing.com/equities/facebook-inc

U.S. Consumer Price Index  	https://www.investing.com/economic-calendar/cpi-733

The CPI is one of the most popular measures of inflation and deflation.
The Consumer Price Index measures the overall change in consumer prices based on a representative basket of goods and services over time.The CPI is the most widely used measure of inflation, closely followed by policymakers, financial markets, businesses, and consumers. (Investopedia)

•	Release Date: CPI data published date
•	Time: CPI data published time
•	Actual: Actual is what the actual reported value for this time is
•	Forecast: Forecast is what the analysts/economists think the value will be this time
•	Previous: Previous is the value of the data the last time it was released

Fed Interest Rate Decision 	https://www.investing.com/economic-calendar/interest-rate-decision-168

An interest rate set by the Federal Reserve to indirectly manage interest rates, inflation and unemployment. The term federal funds rate refers to the target interest rate set by the Federal Open Market Committee (FOMC). This target is the rate at which commercial banks borrow and lend their excess reserves to each other overnight. The FOMC, which is the policymaking body of the Federal Reserve System, meets eight times a year to set the target federal funds rate, which is part of its monetary policy. This is used to help promote economic growth. (Investopedia)

•	Release Date: U.S. Interest Rate published date
•	Time: U.S. Interest Rate published time
•	Actual: Actual is what the actual reported value for this time is
•	Forecast: Forecast is what the analysts/economists think the value will be this time
•	Previous: Previous is the value of the data the last time it was released

![image](https://user-images.githubusercontent.com/113067787/221214625-30863f26-51dc-4d5c-a9f3-eaf7345db3ad.png)

![image](https://user-images.githubusercontent.com/113067787/221214672-06bc4661-83fb-4a87-b254-4bceb04c7cb3.png)

![image](https://user-images.githubusercontent.com/113067787/221214693-62353119-f805-4eae-879c-4aa5e4cdc9ca.png)

![image](https://user-images.githubusercontent.com/113067787/221214821-48aad459-a5be-44eb-988d-64cad3240474.png)


## Results 

The accuracy of the models was tested using a hold-out dataset, and the results showed that first model achieved a high level of accuracy in predicting the prices of the Nasdaq 100 index. The results were compared to the success metrics defined in the product vision, and they met or exceeded the expectations.

![image](https://user-images.githubusercontent.com/113067787/221214940-8b1a33b2-3328-4f9b-a60d-d168bcd696fa.png)

![image](https://user-images.githubusercontent.com/113067787/221214970-7a0be955-8293-4fc9-86ef-4fee7fafa998.png)

![image](https://user-images.githubusercontent.com/113067787/221214987-2a0dc4de-1a82-4f04-bee1-cd88e19e8beb.png)

![image](https://user-images.githubusercontent.com/113067787/221215019-671dda32-a318-4f05-82a7-6e283bdf1a84.png)

![image](https://user-images.githubusercontent.com/113067787/221215036-662b32e7-f561-416a-8e3c-89d746c74623.png)

![image](https://user-images.githubusercontent.com/113067787/221215061-2028047f-5b24-4b75-bad6-cd85e235903c.png)







