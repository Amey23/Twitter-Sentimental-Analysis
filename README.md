# Twitter-Sentimental-Analysis

This is a twitter sentimental analysis model that perform vader sentiment analysis along with tweepy on twitter data which is a Python-based approach. This twitter sentimental analysis is basically for the market research. In order to get this to work we have to fill the APP_KEY and APP_SECRET variables in the python notebook with the credentials that we can get from https://apps.twitter.com.

Authentication:

In order to fetch tweets through Twitter API, one needs to register an App through their twitter account. Follow these steps for the same:

1.	Open https://developer.twitter.com/apps and click the button: ‘Create New App’.

2.	Fill the application details. You can leave the callback url field empty.

3.	Once the app is created, you will be redirected to the app page.

4.	Open the ‘Keys and Access Tokens’ tab.

5.	Copy ‘Consumer Key’, ‘Consumer Secret’, ‘Access token’ and ‘Access Token Secret’.

We follow these 3 major steps in our program:

•	Authorize twitter API client.
•	Make a GET request to Twitter API to fetch tweets for a particular query.
•	Parse the tweets. Find the polarity_score respective of the tweet. Classify each tweet as positive, negative or neutral.
