
## Forecasting S&P 500 Index Closing Price using LSTM and finBERT

Predicting stock market movements holds significant importance for traders, investors, and portfolio managers worldwide, especially amidst the heightened volatility caused by the Covid-19 pandemic and increased market participation. Leveraging advanced machine-learning techniques, such as Long Short-Term Memory (LSTM) models, has become increasingly common due to the growing availability of computational resources.

In this study, LSTM models were employed to forecast the next day's closing price of the S&P 500 index. Data spanning a decade (2010-2020), including fundamental, macroeconomic, technical, and textual data from financial headlines, were collected and utilized for model training. Sentiment scores were derived from the textual data using the finBERT model.

Both single-layer and multi-layer LSTM models were developed and subjected to hyperparameter tuning to optimize performance. Model evaluation was conducted using metrics such as Root Mean Square Error (RMSE), Mean Absolute Percentage Error (MAPE), and Pearson correlation coefficient (R).

Interestingly, single-layer LSTM models outperformed their multi-layer counterparts. Notably, the best-performing LSTM model, featuring a single layer with 10 neurons, exhibited high forecasting accuracy even amidst the unusual market conditions caused by the Covid-19 pandemic.

Moreover, the inclusion of sentiment data from headlines did not lead to improved prediction accuracy, suggesting the limited utility of sentiment analysis in this context.
