# CryptoProphet
This is a project Created for HackUIOWA hackathon.
Devpost Link: https://devpost.com/software/crypto-prophet
In this project, I have extracted past 5 years crypto currency data upto the hackathon date(04/18/2021)from yahoo finance and created data visualization of those crypto market data. I have created box plot,graph area and candlestick for all the major cryptocurrency and then used facebook Prophet to predict price of Dogecoin for next 30 days. This model can be revised to predict any crypto data as well. I also compare the past predictions and compare with the actual values.
Language : Python
Tools used : Google Colab, Plotly Express, Pandas, Facebook PROPHET, Google Sheets
## Inspiration
Current Ongoing craze about the crypto boom, especially after dogecoin reached market cap of 60Billion USD
## What it does
It analyzes past 5 years crypto data of major 12 cryptos, visualize the market evaluation and at the end predicts the crypto price(Dogecoin in this case) for any given time(We chose 30 days) into future
## How we built it
We used google colab and coded in python. We used the panda library and plotly express to visualize the data, also used Facebook PROPHET to predict the Dogecoin price.
## Challenges we ran into
It was a gigantic task to gather this huge amount of data, we collected the past five years of all the available data about major 12 cryptos. Also we had to decide to choose between LSTM and Facebook PROPHET for forecasting crypto data as crypto is the wild west.
## Accomplishments that we're proud of
Our project analyzes 95%-99% of all the available data on cryptocurrency, visualizes these data based on trading volume and price fluctuation and can predict lower bound, upper bound, and the actual price for any crypto currency and any given period into the future.
## What we learned
We learned in-depth about the cryptocurrency market, and time analysis algorithms.
## What's next for Crypto Prophet 
We would like to develop it into a web app or mobile app. We also could develop the data extraction model so that the past data could be updated automatically in it.
