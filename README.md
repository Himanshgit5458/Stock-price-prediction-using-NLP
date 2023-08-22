# Predicting Stock Prices using LSTM and News Sentiment Analysis


![image](https://user-images.githubusercontent.com/96855684/236266774-0770bbf3-53d6-4d56-a928-f30bbc9c19ba.png)



Predicting stock prices is a complex endeavor, influenced by a multitude of factors. This project presents an innovative approach that combines historical stock data and news sentiment analysis to predict stock prices. By harnessing the power of both technical and fundamental analysis, we aim to provide a more comprehensive and accurate prediction model.

## Project Overview

The financial markets are dynamic and driven by a myriad of forces, making accurate stock price prediction a perpetual challenge. Traditional approaches like technical analysis offer insights based on historical price patterns, while fundamental analysis delves into the financial health of a company. Our project goes beyond these isolated methods, merging insights from both technical and fundamental analyses, and introducing the dimension of news sentiment.

## The Challenge

Stock prices are notoriously volatile and can be influenced by factors as diverse as market sentiment, economic indicators, company performance, and global events. The challenge lies in finding a predictive model that effectively captures this intricate web of influences. Traditional technical analysis may overlook the broader context, and isolated fundamental analysis might miss short-term market dynamics. This project addresses these limitations by creating a hybrid model.

## Project Steps

1. **Data Loading and Preprocessing:** We begin by loading historical stock data and news sentiment data. After preprocessing and cleaning, we merge these datasets based on date to enable cross-referencing insights.

2. **Feature Engineering:** Beyond just stock prices, we engineer features that encapsulate both technical and fundamental indicators. This holistic approach empowers the model to consider a wider range of factors.

3. **LSTM Model with Attention:** Our LSTM (Long Short-Term Memory) neural network is enhanced with attention mechanisms, enabling it to focus on relevant features. This dynamic approach can capture evolving patterns and anomalies.

4. **News Sentiment Analysis:** Incorporating news sentiment analysis complements our model by considering news articles' positive, negative, or neutral sentiment. This enriches our understanding of the stock's behavior.

5. **Training and Evaluation:** We train the LSTM model on historical data, validating its performance on separate test data. Our evaluation metric is not limited to accuracy; we also consider interpretability and robustness.

## Project Results

The culmination of our efforts is a stock price prediction model that adeptly combines technical and fundamental insights. By infusing news sentiment analysis, our model demonstrates an ability to grasp market sentiment shifts driven by news events. In empirical tests, our LSTM model achieves a remarkable test score of 2.87 RMSE, significantly surpassing the baseline score of 21.53 RMSE.

## Conclusion

This project contributes to the evolving landscape of stock price prediction by bridging the gap between technical and fundamental analysis. Our multidimensional approach, enriched by news sentiment analysis, underscores the importance of a holistic view. By acknowledging the dynamic interplay of factors shaping stock prices, we empower investors and market enthusiasts with a more informed perspective.

---

We invite you to explore, contribute, and engage with our Stock Price Prediction project. Whether you're passionate about finance, machine learning, or interdisciplinary analysis, your involvement can drive the evolution of this predictive model. Dive into the codebase, experiment with enhancements, and collaborate to uncover deeper insights into stock market behavior.
