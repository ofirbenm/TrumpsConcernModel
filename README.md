# HTML file:
https://ofirbenm.github.io/TrumpsConcernModel/

# Explain:
During first spread of Covif19 the level of concern in the US increased, but at a different pace and at a different level between each political group.
The purpose of the model is to examine the relationship between Trump's tweets and the degree of concern in the United States, to which we have performed the following steps:
1.Filter tweets by searching for corona-related words in each tweet.
2.tokenize per tweet and place a value between 5 and 5 per word depending on its sentiment.
3.The sentiment value scheme for each tweet and the creation of 3 features-
A. Number of tweets per day.
B. The retweet scheme of each tweet that day.
C. The sentiment scheme for each tweet, and then the sentiment scheme of all the tweets that day.
 
Finally we performed a 7-day-average in order to build a balanced model.

The model found that there was a strong correlation between these traits about Trump’s tweets and the degree of concern in the U.S. in line with political views.
