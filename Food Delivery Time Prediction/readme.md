### Food Delivery Time Prediction Model

#### Problem Statement:
The objective of this project is to predict the delivery time of food orders using various features related to the delivery process, such as delivery person details, restaurant and delivery location coordinates, order timing, weather conditions, road traffic density, vehicle condition, type of order, type of vehicle, multiple deliveries, festivals, city, and delivery time.

#### Results:
Based on the performance metrics displayed in the summary table, the Random Forest model consistently outperforms both the Linear Regression and Decision Tree models across all metrics on both the training and testing sets. It exhibits the lowest values for Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE), indicating better accuracy and precision. Additionally, the Random Forest model shows higher R-squared (R2) and Adjusted R-squared (Adj R2) values, suggesting better goodness of fit to the data compared to the other models. Therefore, the Random Forest model is deemed the best model for predicting delivery time in this scenario.

#### Business Conclusions:
The top three factors affecting delivery time are identified as follows:
1. **Road Traffic Density:** High road traffic density leads to delays in delivery as it slows down the movement of delivery vehicles, directly impacting the speed at which orders can be fulfilled.
2. **Multiple Deliveries:** Making multiple deliveries during a single trip increases the overall time spent on the road, especially if locations are spread out or if there are delays in finding addresses or parking.
3. **Delivery Person Age:** The age of the delivery person may influence delivery time, with younger individuals potentially being more agile and efficient, thus completing deliveries faster.

These insights can assist food delivery businesses in optimizing their operations and improving delivery time efficiency.
