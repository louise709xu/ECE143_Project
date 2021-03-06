# ECE143 Project Team 16 - Republican Candidate Tweets

## Members
* Jared	Johann Leitner
* Haonan Song
* Yuchen Tang
* Louise Xu

## Data Gathering Tools
* Tweepy (https://github.com/tweepy/tweepy)
    * Python Twitter API wrapper
    * Limited to last 3200 tweets
    * Requires authentication/developer account
* GetOldTweets-Python (https://github.com/Jefferson-Henrique/GetOldTweets-python)
    * Uses “Advanced Search” feature on Twitter to retrieve tweets
    * Authentication not required, but takes a longer amount of time
    * Not included in the contents of this repo, but can be downloaded from the link above
* Politician Tweets (https://data.world/bkey/politician-tweets)
    * Tweets by US politicians, congress people, senators and governors

## Repo Contents
* get_candidate_tweets.ipynb
    * Note: In order to use Tweepy, you will need to register for a Developer Twitter account (https://developer.twitter.com/)
    * After creating a Developer account, create a file called user_credentials.py and place it in the same directory as user_tweet_scrapper.py
    * Then place your own account details in user_credentials.py in the following format:
~~~~
#Twitter API credentials
consumer_key    = "XXXXXXXXXXXXXXXXXXXXXXXXXX"
consumer_secret = "XXXXXXXXXXXXXXXXXXXXXXXXXX"
access_key      = "XXXXXXXXXXXXXXXXXXXXXXXXXX"
access_secret   = "XXXXXXXXXXXXXXXXXXXXXXXXXX"
~~~~
* metric_visualization.ipynb
    * Matplotlib (https://matplotlib.org/)
        * histograms
    * Bokeh (https://bokeh.pydata.org/en/latest/)
        * scatter plots
        * time series plots
* ratio_plot.ipynb
* sentiment_extraction.ipynb
* word_clouds.ipynb
    * install wordcloud as shown here: https://github.com/amueller/word_cloud
* top5_Tweets_for_Different_Metrics.ipynb
