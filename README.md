# Walmart-Store-Sales-Forecasting

Overview: Walmart is one of the largest retailers in the world and it is very important for them to have accurate forecasts for their sales in various departments.Since           there can be many factors that can affect the sales for every department, it becomes imperative that we identify the key factors that play a part in driving             the sales and use them to develop a model that can help in forecasting the sales with some accuracy.

Info on Data: For this project, we have used the dataset available from ‘Walmart Store Sales Forecasting’ project that was available on Kaggle                                         (https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting/data). In this dataset, we have weekly sales data for 45 stores and 99                   departments for a period of 3 years. In addition, we had store and geography specific information such as store size, unemployment rate, temperature,                     promotional markdowns etc. Using these factors, we needed to develop a regression model that can forecast the sales and is also computationally efficient                 and scalable.

Approach: In this project, we conducted multiple regression models to predict the future sales. There were several different factors that we analyzed in our regression             model starting with a full model with all the variables and then moving forward by eliminating insignificant variables. We used several different exploratory             analyses to identify the key variables for our regression models such as correlation plots, heatmaps, histograms etc.

Output: Test_data_Output.csv was submitted as a sumbmission to Kaggle competetion.

Conclusion: The Random Forest Regression Model turned out to be the best model and predicted the sales with the R2 score of 0.976
