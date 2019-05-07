# KKBOX-Music-Recommendation


### About the company
KKBOX provides a training data set consists of information of the first observable listening event for each unique user-song pair within a specific time duration. 
Metadata of each unique user and song pair is also provided. 
The use of public data to increase the level of accuracy of your prediction is encouraged.

### Data source
The data for this project is from Kaggle - WSDM - KKBox's Music Recommendation Challenge.
The train and the test data are selected from users listening history in a given time period. 
Note that this time period is chosen to be before the WSDM-KKBox Churn Prediction time period. 
The train and test sets are split based on time, and the split of public/private are based on unique user/song pairs.

https://www.kaggle.com/c/kkbox-music-recommendation-challenge/data

### Goal
This project will be focusing on predicting the chances of a user listening to a song repetitively after the first observable listening event within a time window was triggered. 
If there are recurring listening event(s) triggered within a month after the user’s very first observable listening event, its target is marked 1, 
and 0 otherwise in the training set. The same rule applies to the testing set.

### Model Selected
Random Forest, XBboost, LBGM
