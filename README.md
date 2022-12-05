# MachineLearning-InventoryOptimization
### Sprint 1
1.	The box plots and statistics of 27 products, inventory patterns, stock out patterns and missed sales  	
2.	Graphs of best seller and worst seller products of top 25% and bottom 25% and insight into data. (The average selling price of a product is 3$)
3.	Graphs of best and worst products based on their inventory management - Top 25% and bottom 25% and insight into data (the average cost of a product is 0.5$)
4.	Estimation the loss of sales per year per product. Assumption: when we are out of stock, we conservatively lose 75% of the average of sales in the previous 4 weeks on the same weekday
5.	Impact of day of the week on sales and stocks (7 days)
6.	Monthly changes and patterns (for the duration of the data)
7.	Impact of weather condition based on two factors:
i.	Temperature
ii.	Weather condition (sunny, raining, cloudy, etc.)
8.	Investigation whether drive thru feature causes certain products to sell better or worse
9.	Investigation the impact of weekday/weekends and National Holidays by adding extra features
10.	Based on the store data, identify the stocking patterns across multiple stores

### Sprint 2
1.	Produced synthetic data using Generative models (GANs) to get accurate predictions even with little historical data where necessary 
2.	Added weather, weekdays, holidays and temperature data to your features.
3.	Started with a quick linear regression to get a sense of data. Linear regression may not result in a great prediction.
4.	Used ensemble models. Developed the following models and compare the accuracies by comparing the confusion matrix, true positive rate, true negative rate, precision, and F1-score.
a.	Random Forest
b.	Gradient Boosting Machine
c.	Light GBM
d.	XGBoost
5.	Documented and highlighted model improvements
6.	As we are dealing with time-series data, we compared the results of the previous models with the following deep methods:
a.	LSTM
b.	Informer
7.	Based on the results from the models above, we predicted sales based on the following scheme:
a.	Weather forecast i) 1 day ahead ii) 3 days ahead (shipping from corporate warehouse) iii)10 days ahead (distributer order to the manufacturer) 
b.	Week of the day
8.	Used 80% of data for training and 20% of data for testing



