# TravelTime
A machine learning model to predict the time needed to travel from one location to another.

## Steps
Here are the steps I passed through when I was implementing the model.
1.  Read the data then get general informations about the data.
2.  handled missing values.
3.  Extracted features from the date feature.
4.  Encoded data using one hot Encoding
5.  Visualised data using Matplotlib
6.  Used kmeans algorithm to gather near locations together (using latitude and longitude features) and then add a new features "pickup" and "dropoff".
7.  Used a machine learning algorithm (XGBRegressor in my case) to train the model and make predictions.


## Dataset
The dataset used to train the model is taken from a public competition on [Zindi](https://zindi.africa/).
If you're a dataset owner and do not want your dataset to be included here, please get in touch through a GitHub issue. Thanks for your contribution to the ML community!
