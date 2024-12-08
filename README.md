REDDIT STOCK SENTIMENT ANALYSIS
This project scrapes recent posts from the r/wallstreetbets subreddit, analyzes the sentiment of each post, and performs a machine learning-based sentiment classification to determine whether the sentiment around a given stock is positive, negative, or neutral. The project uses Reddit's API (praw), Natural Language Processing (NLP) techniques, and a Random Forest model for classification.

FEATURES:

Scrape Reddit Data: Scrapes recent posts from the r/wallstreetbets subreddit.
Text Preprocessing: Cleans and processes the scraped text data to remove URLs, special characters, and convert the text to lowercase.
Sentiment Analysis: Analyzes the sentiment of the posts using TextBlob. Classifies the sentiment as positive or negative based on polarity.
Stock Sentiment Analysis: Allows users to input a stock name to analyze the overall sentiment (positive or negative) for the stock based on Reddit posts.
Machine Learning Model: Uses a Random Forest classifier to predict the sentiment of posts based on the title.
Model Evaluation: Provides the accuracy and classification report of the trained model.

REQUIREMENTS:
Python 3.x
praw – Python Reddit API Wrapper
textblob – Text Processing and Sentiment Analysis
pandas – Data Manipulation and Analysis
scikit-learn – Machine Learning Library


SETUP:
Reddit API Credentials:
You need to create a Reddit app to get your API credentials. Visit Reddit's app preferences to create your app and obtain the following:

client_id
client_secret
user_agent
Replace the client_id, client_secret, and user_agent in the script with your actual values.



Scrape the latest posts from the r/wallstreetbets subreddit.
Clean and preprocess the text.
Perform sentiment analysis using TextBlob and machine learning (Random Forest).
Print the sentiment analysis result for a stock entered by the user.
Output the model's accuracy and classification report.
Usage
Once the script is executed, it will display a prompt for you to input a stock name. The program will then:

Filter posts related to the stock.
Count the positive and negative sentiment posts.
Display whether the stock has a Positive, Negative, or Neutral sentiment.
Example:

Enter your favorite stock to analyze sentiment: Tesla
Sentiment for Tesla: Increasing (Positive sentiment: 120, Negative sentiment: 80)


Sentiment for a Stock: Based on the analysis of the posts, the program will output whether the sentiment around a given stock is positive, negative, or neutral.






