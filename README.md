# CS460-Project
Future sales prediction

**Project**: Try to predict total sales for the upcoming months for the russian software firms(whoose sales data of Jan-2013 to Dec-2015, we are using). We use three models ARIMA, ETS and LSTM.
- **Data**: It is available in the kaggle website(https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data). You need to download "items.scv" and "sales_train.csv" 
- **Arima,ETS_1** : Consist of Arima and ETS on date vs item sale, statinority test.
- **Arima,ETS_2** : Consist of Arima and ETS on week vs item sale, statinority test.
- **Arima,ETS_3** : Consist of Arima and ETS on month vs item sale, statinority test.
- **LSTM_1 for CS460**: Consist of univariate LSTM, data conversion and Case-1 for multivariate analysis(where all the shop_id were considered as features).
- **LSTM_2 for CS460**: Consist of Case-2 for multivariate analysis(where all the item_category_id were considered as features).

NOTE: I used python ver 3.6.10 and keras ver 2.3.1
