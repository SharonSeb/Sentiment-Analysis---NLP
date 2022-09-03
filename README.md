# Sentiment Analysis - NLP
**Background and Context:**

Twitter possesses 330 million monthly active users, which allows businesses to reach a broad population and connect with customers without intermediaries. On the other hand, there’s so much information that it’s difficult for brands to quickly detect negative social mentions that could harm their business.

That's why sentiment analysis/classification, which involves monitoring emotions in conversations on social media platforms, has become a key strategy in social media marketing.

Listening to how customers feel about the product/service on Twitter allows companies to understand their audience, keep on top of what’s being said about their brand and their competitors, and discover new trends in the industry.

Present dataset has tweets related to 6 leading US airlines. The sentiment of each tweet is also added.

**Data Description:**

A sentiment analysis job about the problems of each major U.S. airline. Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service").

**Dataset**:

The dataset has the following columns:

tweet_id
airline_sentiment
airline_sentiment_confidence
negativereason
negativereason_confidence
airline
airline_sentiment_gold
name
negativereason_gold retweet_count text tweet_coord tweet_created tweet_location user_timezone

**Objective**:

The purpose of this project is to explore the numerous features and build a classification model where we will be able to tag the sentiment based on the tweet text and consequently label them positive, negative and neutral. We will be using different data processing steps to reduce the dimensionality and get the best words which will help in the classification. Models based on countvectorizer and Td-idf will be compared based on accuracy scores.
