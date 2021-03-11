# Analysis of Donald Trump's Twitter Account During the 2016 and 2020 Presidential Campaign
Final project for graduate course ITEC-596: Python for Programming Business Analytics

## Data Set:
The data for this analysis was gathered from the [Trump Twitter Archive](http://www.trumptwitterarchive.com/). The website was created by Brendan Brown and it includes nearly all of Trump's tweets from 2009 to the present day, with the exception of 4,000 tweets missing from the archive and any tweets that Trump deleted prior to September 2016. I created a dataset for Donald Trump's tweets from 2016, 2020 (up until October 24th) and a combined dataset. The 2016 dataset contains 4,225 tweets. The 2020 dataset contains 10,263 tweets.

The original variables include:

- **id:** Identifying ID  for the individual tweet.
- **text:** The text of the tweet.
- **isRetweet:** If the tweet is a retweet or not.
- **isDeleted:** If the tweet was deleted or not.
- **device:** What device/platform was used to post the tweet.
- **favorites:** Total count for how many times the tweet was favorited.
- **retweets:** Total count for how many times the tweet was retweeted.
- **date:** The date and time the tweet was posted.

Throughoug the duration of the project the following variables were created:

- **Image:** If the tweet contained an image or not.
- **clean_text:** Cleaned text of the tweet
- **mentioned:** The handle of who was mentioned.
- **hashtags:** The text of the hashtag(s).
- **character_len:** Character length of tweet.
- **word_count:** Word count of tweet.
- **tweet_year:** The year of the tweet.
- **blob polarity:** TextBlob polarity score.
- **blob_subjectivity:** TextBlob subjectivity score.
- **TextBlob:** TextBlob Sentiment.
- **TextBlob_Subjectivity:** TextBlob Subjectivity.
- **neg:** Vader negative score.
- **neu:** Vader neutral score.
- **pos:** Vader positive score.
- **compound:** Vader compound score.
- **VADER:** Vader Sentiment.
- **Topic_LDA:** LDA Topic.
- **Topic_NMF:** NMF Topic.
