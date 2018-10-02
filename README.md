# news_analytics
homework for Social Analytics "News Mood" 

This program will provide a visualized summary of the sentiments expressed in Tweets sent out by the following news organizations: **BBC, CBS, CNN, Fox, and New York times**. It will produce a scatter plot of sentiments of the last **100** tweets sent out by each news organization, ranging from -1.0 to 1.0, reflecting the compound sentiments analyzed by VADERm for each tweet. The scatter plots will be exported to the results folder under the names scatter1.png - scatter5.png

It will Perform a sentiment analysis with the compound, positive, neutral, and negative scoring for each tweet and export the data  into a CSV file news_tweets.csv in the results folder.

Finally it will visualize the overall sentiments of the last 100 tweets from each organization using a bar graph of the mean of the compound sentiments analyzed by VADER. This graph will also be exported to the results folder and named bargraph.png

# Analysis

1 While the overall compound score of each news source may be positive or negative, the scatter plot shows that none of them is all positive or negative, but have a broad range of sentiment scores. 

2 The most prevalent score is 0 resulting in a line at the 0 point in 4 out of 5 scatters with Fox having the most solid line.

3 The bar graph shows that BBC, CBS, and New York Times are more typically negative while CNN is more typically postive with Fox positive,but less so. (bargraph1.png, 10-1 17:05) (bargraph2.png,10-2 11:39 am) 

4 I changed the scale of my bar graph to (-1, 1) (bargraph.png, 10-2 15:49) This was helpful in showing that the mean composite scores are relatively very close to 0 for all the news sources.

