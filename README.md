# Air Passenger Traffic Forecasting using Community Detection and LSTM

The Aviation industry has seen a significant growth in the recent years and has contributed to the upturn in the global economy. Air passengers forecasting has become inevitable for the operating airlines to plan their flights to cope up with the growing demands and the passengers can also plan their journey beforehand. The main objective of this paper is to predict the trends in the number of passengers travelling all over the world. As the travel trends differ from season to season and certain airports are busier than others, the predictions would be more specific, if it is based on seasons and hubs. In order to identify strongly connected routes and city pairs in the air transportation network, the Louvain algorithm for community detection is used. The busiest hubs are identified using this algorithm and then, season-wise forecasting is implemented for air passengers traffic. Long Short Term Memory(LSTM) model along with k-fold cross validation is used for the prediction purpose. The performance of the LSTM model is then evaluated using standard error metrics such as Mean Absolute Error(MAE),R2 score and adjusted R2 score.

The datasets used in this project are retrieved from the following links, which are also available in the main report:
* Domestic US passengers data - https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=GED 
* International US passengers data - https://data.transportation.gov/Aviation/International_Report_Passengers/xgub-n9bw


The main report for this project is added in docs/documentation folder.

The source code used for this implementation is placed in src/code folder.