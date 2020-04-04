# Twitter_Sentiment_Analysis


### Tweepy Documentation
http://docs.tweepy.org/en/latest/


### Specify what user we want to extract tweets from and how many tweets to extract
`tweets = api.user_timeline(screen_name="realDonaldTrump", count=20)`

### Dropping tweets from a user onto a dataframe 
`df = tweet_analyzer.tweets_to_data_frame(tweets)`
