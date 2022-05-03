# Sentiment Analysis Twitter Users
Checks the Subjectivity and Polarity of tweets by Twitter users 
# Objective
The objective of this task is to detect the polarity of opinions in tweets. For the sake of simplicity, we say a tweet is negative if it has racist, sexist or contains other sentiment categorised this way. So, the task is to classify these tweets from other tweets.
## Obtaining, Processing and Cleaning
The analysis uses the twitter API to access the latest tweets from a specified user. These tweets are then cleaned, getting rid of characters regarded as unnecessary. They include symbols, @mentions, RT labels, hashtags and hyperlinks.

The analysis then runs the tweets through a subjectivity and polarity function that has been defined. It examines the sentiment distribution of tweets and provides a visual representation using word cloud.
## Ending Notes
The subjectivity and polarity index obtained from the functions enable the analysis to compute, determine and classify the tweets either as positive, negative or neutral. The indices are generated depending on the type of words used in the tweets.