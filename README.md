# What Are People Saying About Airline Companies On Twitter?  
---

I used natural language processing (NLP) to extract a list of topics from tweets about airlines. I used the Twitter API to collect over 60,000 tweets about four major airlines over the course of two weeks. I discovered conversations about ten topics ranging from customer service, to having fun and traveling, to racism.  

The tweets were stored in MongoDB.  

I wrote my own cleaning module to handle twitter specific issues such as slang, emojis, twitter handles, and misspellings.  
I used [spaCy](https://spacy.io/) to tokenize and build my corpus.  
I used Latent Semantic Analysis (LSA) and KMeans clustering to generate my list of topics.  

There are six notebooks in my repository:  
1. [Getting tweets](https://github.com/ericchan24/airline_twitter/blob/master/notebooks/01.%20get_tweets.ipynb)  
2. [Cleaning and sentiment analysis](https://github.com/ericchan24/airline_twitter/blob/master/notebooks/02.%20cleaning_and_sentiment_analysis.ipynb)  
3. [More cleaning](https://github.com/ericchan24/airline_twitter/blob/master/notebooks/03.%20more_cleaning.ipynb)  
4. [Lemmatizing](https://github.com/ericchan24/airline_twitter/blob/master/notebooks/04.%20lemmatize.ipynb)  
5. [Topic Modeling using Latent Semantic Analysis](https://github.com/ericchan24/airline_twitter/blob/master/notebooks/05.%20topic_modeling_lsa.ipynb)
6. [Final Model using LSA and KMeans clustering](https://github.com/ericchan24/airline_twitter/blob/master/notebooks/06.%20final_model.ipynb)  

Here is a link to an interactive app that I made to summarize my project  [Airline Tweets](https://airline-tweets.herokuapp.com/)  
Here is a link to my blog post about the project. [Blog Post](https://ericchan24.squarespace.com/blog/analyzingairlinetweets)
