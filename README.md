
# tweets scraping and analysis

About this project:

The purpose of this project is to get data from Twitter for sentiment analysis. 
Then we will find the pattern of likes, comments and retweets of different types of tweets. 

Then we created a word cloud to see what the frequent words the politicians are using. We found the words like "today", "American", "people", "will", "make", "vote", "back better" and "build back" are more prominent in the plots. It seems to me that the politicians are giving hope to the readers.  Box plot and histogram below show all types of responses are extremely right-skewed. 
Also, the number of likes outweigh the number of retweet and comment. Lastly, we have a pivot table to show the median of responses of all types of tweets. We found that the original and positive tweets get more answers, while the neutral and non-original tweets have the least likes, retweets and comments. 

Difficulaities:

Since I do not have the Twitter API, I use the selenium package to get the data. There is a backlash against using selenium on continuous scrolling pages. Some tweets are missed because it is hard to control the scrolling and Internet speed. But still, we capture nearly 2000 tweets for analysis.

Next steps:

Statistical testing is needed to tell if the difference between all the groups is statistically significant.
