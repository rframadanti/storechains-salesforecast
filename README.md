# storechains-salesforecast
Applying data analytics process and building forecasting models for health & beauty retail stores

Forecasting sales is important in retail business to ensure operational efficiency and increase profitability. The datasets contains data of a drug store chain with 1,115 stores to be analysed. There are 3 datasets:
1. Store dataset which contains information of stores' profile such as their StoreType and Assortment type.
2. Train dataset which contains all the stores' 31 months of past daily sales data.
3. Test dataset which contains all the stores' 6-weeks incoming information whose sales need to be predicted.

Data analytics process was applied to predict their sales. 
The data was explored, visualised and pre-processed appropriately before applying predictive analytics with the most robust model and applying the forecasting technique. 

Several predictive models were built which included:
1. Multiple Linear Regression (with Python)
2. Multiple Polynomial (Cubic) Regression (with SAS Entreprise miner)
3. Decision Tree Regression (with SAS Entreprise miner)
4. Random Forest Regression (with Python)
5. Gradient Boosting (with Python)
6. Neural Network (with SAS Entreprise miner)
7. Auto ARIMA (with Python)
8. SARIMA & Auto SARIMA (with Python)

The models were validated using both random 80:20 training:validation validation and out-of-sample validation and their RMSE were calculated and compared.
Finally the Random Forest model was chosen for the final forecast of the 6-weeks sales because it had the best prediction accuracy of 1111 RMSE from the historical data.

The analysis indicated that in-store promotions have the highest positive impact on sales. It also showed a weekly cycle and a pattern of seasonality as the end-of-year period generated the highest sales. The data should further be enriched with more information on pricing, product variety, locations and the launch of new products, to enable more powerful forecasting. 
