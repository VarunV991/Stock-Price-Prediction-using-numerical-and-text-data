# Stock Price Prediction using numerical and text data

![Python 3.7](https://img.shields.io/badge/Pyhton-3.7-blue) 

## Objective

The objective of this project is to forecast the closing price of a stock based on the <strong>historical data of the stock and the news headlines of the chosen stock</strong>. 

## Directory Tree 

```
├── lexicon_data
├── models
├── historical_data.csv 
├── Hybrid Model.png
├── MinMaxScaler
├── model.h5
├── model.json
├── README.md
├── Sentiment Analyzer
├── Stock Market Prediction using Numerical and Textual Analysis.ipynb
```

## Dataset

The numerical dataset of BSE Sensex is taken from Yahoo Finance. This dataset contains last 15 years of stock details of BSE Sensex. The dataset link is given <a href="https://finance.yahoo.com/quote/%5EBSESN/history?p=%5EBSESN">here</a>.
The text dataset is taken from Harvard dataverse. This dataset contains the last 20 years news headlines of different categories published in Times of India. The dataset link is given <a href="https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DPQMQH">here</a>.

## Model Structure

The whole hybrid model which combines the insights from text and numerical data is represented below:<br>
<center><img src="Hybrid Model.png"><center>

## Code

The code for the model, algorithms used and accuracy of the model can be found <a href="https://github.com/VarunV991/Stock-Price-Prediction-using-numerical-and-text-data/blob/master/Stock%20Market%20Prediction%20using%20Numerical%20and%20Textual%20Analysis.ipynb">here</a>.
The trained model weights is available <a href="https://github.com/VarunV991/Stock-Price-Prediction-using-numerical-and-text-data/blob/master/model.h5">here</a>.

