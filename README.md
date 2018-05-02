
## Problem
In this competition, Kaggle is challenging you to build a model that predicts the total ride duration of taxi trips in New York City. Your primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.



## Data
1. id - a unique identifier for each trip
2. vendor_id - a code indicating the provider associated with the trip record
3. pickup_datetime - date and time when the meter was engaged
4. dropoff_datetime - date and time when the meter was disengaged
5. passenger_count - the number of passengers in the vehicle (driver entered value)
6. pickup_longitude - the longitude where the meter was engaged
7. pickup_latitude - the latitude where the meter was engaged
8. dropoff_longitude - the longitude where the meter was disengaged
9. dropoff_latitude - the latitude where the meter was disengaged
10. store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip
11. trip_duration - duration of the trip in seconds


## Methods

The result could rank in first 30%. Feature engineering: combine several datasets and adjust according to timestamp. Use K-means, Randomforest to generate features. Training model: compare K-NN, Linearegression, Xgboost and tune parameters. Then compare Xgboost model treating “outliers” as outliers or other behaviors.

## Results
![image](https://user-images.githubusercontent.com/28909028/39531283-6b5bb164-4df0-11e8-86c8-c844efcee0f3.png)





