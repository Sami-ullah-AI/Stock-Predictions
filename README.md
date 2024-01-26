# Stock-Predictions
The stock market is known for its volatility, making it a fascinating area for researchers and 
statisticians to predict stock prices. Despite extensive research in this field, many experts still 
believe that stock markets cannot be predicted due to the numerous factors affecting stock prices 
and their interdependence on other unknown factors. The commonly used approach for stock 
market prediction is to use past experiences in price changes to predict future prices. However, 
financial forecasting is a challenging task due to small sample sizes, high noise, non-stationarity, 
and non-linearity, making it difficult to get accurate predictions.
This thesis aims to address this problem by using machine learning, specifically deep neural 
networks, to predict stock prices. The research consists of two parts: the first part focuses on 
learning the context and impact of news articles on stock prices using Long-Short Term Memory 
(LSTM), and the second part aims to learn how general trends and news can be combined to make 
accurate predictions of stock values using a deep network. The use of news articles for stock 
market predictions has been explored in previous research, but this thesis aims to offer different 
and potentially better results. Most previous studies apply sentiment analysis to news articles, but 
this approach may not always work, especially when the impact of the news is not felt immediately. 
This thesis aims to predict which articles are relevant to the stock market and use them to make 
accurate predictions.
Another critical factor affecting stock prices is the correlation between stocks. All stocks are 
related by some variable factor, and if any two stocks are related, there may be a causation between 
the two, especially if the Pearson's correlation coefficient is high. Despite the importance of 
correlation for stock traders and investment companies, there is limited research in this area by 
computer scientists. This thesis aims to address this issue by examining the impact of correlated 
stocks on a company's stock prices.
Finally, the thesis aims to merge the above two solutions to achieve a more accurate stock market 
prediction and convert this into a website. The prediction accuracy will be verified by comparing 
it with a simple deep network on the same data, without the correlated stocks or the LSTM data
