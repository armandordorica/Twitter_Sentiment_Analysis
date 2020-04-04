# Twitter_Sentiment_Analysis


### Tweepy Documentation
http://docs.tweepy.org/en/latest/


### Specify what user we want to extract tweets from and how many tweets to extract
`tweets = api.user_timeline(screen_name="realDonaldTrump", count=20)`

### Dropping tweets from a user onto a dataframe 
`df = tweet_analyzer.tweets_to_data_frame(tweets)`


### See all the information that a tweet objct has available 
`print(dir(tweets[0]))`


### Examples of extracting main features that a tweet has
```python
    print("Tweet text: {}".format(tweets[0].text))
    print("Tweet language: {}".format(tweets[0].lang))
    print("Tweet location: {}".format(tweets[0].geo))
    print("Tweet coordinates: {}".format(tweets[0].coordinates))
    print("Tweet favorite_count: {}".format(tweets[0].favorite_count))
    print("Tweet retweet_count: {}".format(tweets[0].retweet_count))
```
