

Prediction of Twitter Retweet Count Based on Twitter data

Team-Supernova
Members-Teena Gorge, Ao Li, Qianyi Li, Yuxi Wu, Yaxin Chen

We collect movie reviews from twitter, weeks before and after the release of movies and calculate the sentiment score for each movie. We analyze various variables from Twitter such as, retweet counts, followers count, and other variables related to a movie such as, budget, box office collection, actor rating, director rating etc. We try to identify the correlation among various variables. Also, we try to predict the retweet count using three different data mining techniques-decision tree(CHAID), k means clustering and neural net.

We considered 14 movies and collected all the required variables. We calculated the sentiment score of each movie using VADER. The correlations were studied from charts made in Tableau and Excel. We found that there is no specific relationship between the sentiment score and box office collection. Similarly, we failed to identify a correlation between compound score and retweets. Another finding is that the tweets about feeling, film type and actor usually have higher retweet count when it is more positive, while tweets about director have higher retweet when it is more negative.

We can see that a movie with lowest sentiment score has a very high retweet count while another movie with around the same sentiment score has a low retweet count, which could be because when a highly anticipated movie gets a bad review, it tends to spread very quickly. This shows that still word of mouth(retweets) is a popular method for promoting movies.

In terms of timing of tweets, we observed that tweets posted in the first week after the film released have higher average retweet count and usually have high sentiment score and that in the second week, the retweets dropped down dramatically. However, second week seems to be very important for box office collection as the total compound score and box collection is the largest in this week. The box office collection must have increased in the second week due to large number of retweets in the first week. Therefore, we further analyzed retweets using SPSS Modeler. Ultimately, compared to K-means clustering, Neural Network and Decision Tree, Neural Network performed better with nearly 80% accuracy. As a result, we found that competition factors and weeks are the most important factors to predict retweeted number.





