# Project 3: Web APIs & NLP and Sentiment Analysis

#### Executive Summary

In this project, I am comparing two subreddits whose data was gathered by webscraping using an API. The data was then trained using NLP and then classified using different models.  The subreddits I chose to compare are the r/disneyworld and r/universalorlando.  I combined 2000 posts from both subreddits and compiled the title and self text columns into one column called title_text.  This was then processed using NLP and run through models.  The model that preformed the best was Multinomial Naive Bayes.  I then performed a sentiment analysis and found Disney World posts had a higher positive sentiment rate.

---

#### Problem Statement

The posts from the r/universalorlando and r/disneyworld reddit pages have somehow been combined and mixed up.  Reddit needs to be able to fix this error and put the correct posts on the subreddit that they go on.  I am creating models to predict which subreddit a post goes on.  I am also performng a sentiment analysis to se which subReddit will be graded higher.

---

#### Data Cleaning and EDA

Data from both subreddits were combined into one data frame and then the title and self text was combined into.  The data was cleaned by removing special characters and numbers from the data frame.  The data was then lemmatized before being put into the models.



---

#### Subreddits

The r/disneyworld and r/universalorlando subreddits are used by those who are planning trips to the different parks and getting questions answered.  Also, fans or passholders of both parks post on the Reddits about their experiences.

 [r/DisneyWorld](https://www.reddit.com/r/DisneyWorld)
 
 [r/UniversalOrlando](https://www.reddit.com/r/UniversalOrlando)
 

---

#### Frequent Words


I created a plot to show the words used most frequently in both subreddits.  


![Most frequently used words](https://i.imgur.com/Bl47Mx4.png)

---
#### Models

Cvec, Tfidf, and Naive Bayes all scored close to the same score. The Multinomial Naive Bayes achieving the best accuracy score with 88.9% accuracy.

---
#### Sentiment Analysis

I performed a sentiment analysis on the two subreddits.  I graded the posts as positive, negative, or neutral according to the lists of positive and negative words I created.  FOr posts that were not neutral, Disney posts were 95% positive while Universal posts were 90% positive.  Based upon this, I would recommend Disney World for those who are planning to vacation in Orlando.



