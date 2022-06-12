# WeRateDog-
WeRateDog Twitter dog rating analysis
In the Data wrangling process, I gathered data from three pieces of data sources which are 1) The WeRateDogs Twitter archive csv file already provided from Udacity. 2). This file (image_predictions.tsv)present in each tweet according to a neural network. It is hosted on Udacity's servers and should be downloaded programmatically using the Requests library and the 3).The third source was gotten from the Twitter API using Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file.   The JSON .txt file contains the  tweet ID, retweet count, and favorite count of the WeRateDog twitter archive   

The Data wrangling provides a clean data frame for future analysis and
visualization, in our case, we stored the cleaned data into a new csv file titled
‘twitter_archive_master.csv’.
