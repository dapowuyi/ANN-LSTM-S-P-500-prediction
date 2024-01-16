# ANN-LSTM-S-P-500-prediction
A hybrid ANN-LSTM model to predict the S&amp;P 500 index.
There are 6 models in the project - An ANN model, LSTM and ANN-LSTM applied only to the close price. These three are then applied to the close price integrated with eonomic data and technical factors.
There are different datasets utilised. 

The main datset for the S&P 500 which is the historcal data between January 2018 to December 2022. Then there is the GDP data, the Interest rate, unemployment rate, consumer sentiment data and finally the infalation/CPI dataset. All of these were combined with five (5) technical indicators namely EMA7, SMA 50, SMA 100, SMA 200 and RSI. 

The final dataset called "Final_Sp_data_Eco_Tech.csv" containing of the merged data was used for the predictions. Additionally, I spooled the predicted vs actual values into a dataframe which I used to creat a dashboard. That files is the dashboard_data.csv. The link to the dashboard code is found here https://www.pythonanywhere.com/user/papi501/files/home/papi501/s_p500_dashboard/sp_500_dashboard.py. The dashboard itself can be found here http://papi501.pythonanywhere.com/
