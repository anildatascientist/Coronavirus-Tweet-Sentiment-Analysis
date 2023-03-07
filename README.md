![Read me Image](https://user-images.githubusercontent.com/59911959/189983631-8b1a97c9-07e9-4a2f-8297-db2c5da3bd6c.png)


# 📋 Abstract:
Twitter is American microblogging and social networking service on which users post and interacts with messages known as "tweets". We all know Covid-19 has greatly impacted our lives in many ways. There has been good and bad news all over the world and people have been responding to it on Twitter. So my project is about classifying the tweets into positive, negative, and neutral using different classification models. In the end, we compare their performance and find which one is better.

# Introduction:
There have been a lot of incidents, both good and bad all around the world. People have written their views on those situations on many social media sites. One of them is Twitter, and we have performed a sentiment analysis on thousands of tweets in our data set to come up with a classification model and segregate those tweets into – positive, negative, and neutral.

# 🎯 Business Requirement:
The CoVid-19 pandemic has shaken the very foundation of society wherein people were forced to live inside their houses because of the lockdown being imposed and also the livelihood of almost every section of the society was impacted.

The objective of our analysis revolved around knowing the sentiments of people from their tweets on Twitter as Twitter is one of the prime means of expression over social media

# Data Summary:
• UserName
 
• ScreenName

• Location (Location of the tweet)

• TweetAt (Date/Time of tweet)

• OriginalTweet (The string of the tweet)
 
• Sentiment

As the first two columns username and screenname column contain integer data and they will be of no use for performing the modeling and analysis. We need two columns, original tweet and sentiment to perform modeling and also need other features for EDA.
Twitter is a big platform to post any statuses, the same we have provided the posts data of twitter related to covid-19.
The data that we worked on here has been scrapped from Twitter itself and manually labeled.

There are a total of 5 sentiments in the dataset as follows.

1.	Extremely Positive

2.	Positive

3.	Neutral

4.	Negative

5.	Extremely Negative


# Conclusion and Insights:
* We conclude that the machine is generating the best results for the Logistic Regression with Grid Search CV (count vectorizer) model with an Accuracy of 78.28% followed by the Logistic Regression with Grid Search CV (TF/ID vectorizer) model with an Accuracy of 77.43%.
* Also, we observed that no overfitting is seen for the data, and we can deploy this model.
* Even being in the unprecedented situation of CoVid-19, people's positive sentiments outnumbered negative sentiments.
* However, negative sentiments also has a significant chunk which various Government agencies, NGOs, etc can use to help boost the morale of the people and then
* In the future ,we can repeat the analysis and compare it with the present sentimental analysis to gauge the impact of the initiatives on the ground.

📚 References
Random Forest Regressor: 
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html

Gradient Boosting Documentation: 
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html
