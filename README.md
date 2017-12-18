# What Are People Saying About Airline Companies On Twitter?  
---

I used natural language processing (NLP) to extract a list of topics from tweets about airlines. I used the Twitter API to collect over 60,000 tweets about four major airlines over the course of two weeks. I discovered conversations about ten topics ranging from customer service, to having fun and traveling, to racism.  

The tweets were stored in MongoDB.  

I wrote my own cleaning module to handle twitter specific issues such as slang, emojis, twitter handles, and misspellings.  
I used ![spaCy](https://spacy.io/) to tokenize and build my corpus.  
I used Latent Semantic Analysis (LSA) and KMeans clustering to generate my list of topics.  

There are six notebooks in my repository:  
1. Getting tweets  
2. Cleaning and sentiment analysis  
3. More cleaning  
4. Lemmatizing  
5. Topic Modeling using Latent Semantic Analysis  
6. Final Model using LSA and KMeans clustering

Here is a link to an interactive app that I made to summarize my project  ![Airline Tweets](https://airline-tweets.herokuapp.com/)
Here is a link to my blog post about the project. ![Blog Post](https://ericchan24.squarespace.com/blog/analyzingairlinetweets)
