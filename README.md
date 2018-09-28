# Information
- Title: New York City Taxi Fare Prediction
- Website: https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/
- Purpose:
    - *In this playground competition, hosted in partnership with Google Cloud and Coursera, you are tasked with predicting the fare amount (inclusive of tolls) for a taxi ride in New York City given the pickup and dropoff locations*

    
- Scoring Metric: RMSE (root-mean-squared error)
    - A large RMSE is equivalent to a large average error, so smaller values of RMSE are better.
    - What does this mean? We are calculating the difference between the prediction and the ground truth. We are the squaring the results. If the difference is positive or negative, the concern should be on the magntitude. We then are calculating the average (to normalize the results per observations). Lastly, we are squaring the results to normalize the results in the same measure.
