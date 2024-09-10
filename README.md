# Fake-News-Prediction

##  Project overview:

This project aims to analyze and detect fake news using machine learning approach. The system processes news articles, breaks them down into smaller chunks for analysis, and leverages LLMS to classify articles base on their factuality. This helps to identify misinformation and unreliable sources in the news.

##  Dataset:
Dataset obtained from kaggle: https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets
Data contains: Title, Text, Subject, Data and Label

##  Approach 1:
Roberta for sequence classfication

##  Approach 2:
Obtain article and compare for cosine similarity score

##  Current Approach：
LLM for summarization and cross validation

### Model used: LLAMA 3 70B 
api source: https://groq.com/

##  Example:
1. article will be rephrased into summarized points
2. each point will be searched online for related articles
3. it will be verified as true if related articles by credible sources are found

## Result
Accuracy for current method on sample fakenews is at 75%
