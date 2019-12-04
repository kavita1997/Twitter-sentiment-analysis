# Twitter Sentiment Analysis

Sentiment Analysis is a term that you must have heard if you have been in the Tech field long enough. It is the process of predicting whether a piece of information (i.e. text, most commonly) indicates a positive, negative or neutral sentiment on the topic. In this article, we will go through making a Python program that analyzes the sentiment of tweets on a particular topic. The user will be able to input a keyword and get the sentiment on it based on the latest 100 tweets that contain the input keyword.

# Installation Required

Tweepy

Textblob

# Authentication:

In order to fetch tweets through Twitter API, one needs to register an App through their twitter account. Follow these steps for the same:

Open this link and click the button: ‘Create New App’

Fill the application details. You can leave the callback url field empty.

Once the app is created, you will be redirected to the app page.

Open the ‘Keys and Access Tokens’ tab.

Copy ‘Consumer Key’, ‘Consumer Secret’, ‘Access token’ and ‘Access Token Secret’.

# We follow these 3 major steps in our program:

Authorize twitter API client.

Make a GET request to Twitter API to fetch tweets for a particular query.

Parse the tweets. Classify each tweet as positive, negative or neutral.
