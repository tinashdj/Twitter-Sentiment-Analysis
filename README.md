# Twitter Sentiment Analysis
Sentiment analysis is using to identifying as well as classifying the sentiments that are expressed in the text form. Twitter sentiment analysis allows you to keep track of what’s being said or tweets on twitter as a social media. Tweets can often produce a significant amount of sentiment data after analyzed. These data can help us understanding the opinion from people about a variety of topics. This project intends to use various text cleaning techniques to extract information from Tweets. The dataset I am using here for the project of twitter sentiment analysis is downloaded from Kaggle.

## Data Cleaning
1. Removing null value
2. Changing entire row to lower case
3. Removing Punctuation
   - Remove user mentions from the tweets
   - Remove hashtags from the tweets
   - Remove links/urls from the tweets
   - Another text processing
4. Removing Stop Words

## Data Exploration

1. Show the total percentage of each sentiment.
  
   Negative sentiment with 30.2% total sentiments as the most sentiment. Second we have Positive sentiment with 27.9% total sentiments. Third is Neutral sentiment with 24.5% total sentiments and fourth or the least sentiment is Irrelevant sentiment with 17.4% total sentiments.

   ![FireShot Capture 035 - Twitter Sentiment Analysis - Jupyter Notebook - localhost](https://github.com/tinashdj/Twitter-Sentiment-Analysis/assets/110084624/c6568677-4661-4a01-b7bf-360d288f948f)

2. Showing the top 30 words that appear frequently on positive and negative sentiment.

   In Positive sentiment we can see some positive words, like love, good, best, great. In Negative sentiment, instead, we observe lots of swear words. Both Positive and Negative sentiments, the word "game" appears in both sentiments as the top word that appears most often. In Positive sentiment the "game" word appears with more than 2.000 times while in Negative sentiment the "game" word appears more than 3.500 times. In addition to the word "game", other words appear between the number of times more than 500 to almost 2000 times.
   
   ![FireShot Capture 038 - Twitter Sentiment Analysis - Jupyter Notebook - localhost](https://github.com/tinashdj/Twitter-Sentiment-Analysis/assets/110084624/c7076bca-0e38-4e02-bd62-779aa7cbeb14)

3. Showing the frequent words on positive and negative sentiment using WordCloud.
   
   In "Positive" sentiment we can see some positive words, like love, good, best, great. In "Negative" sentiment, instead, we observe lots of swear words. In short, the distribution of the most frequently used words differerent for each type of sentiment.

   ![FireShot Capture 039 - Twitter Sentiment Analysis - Jupyter Notebook - localhost](https://github.com/tinashdj/Twitter-Sentiment-Analysis/assets/110084624/e7f80cec-30f8-41e9-81ff-10757a95ad52)
