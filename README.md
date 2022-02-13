[Stock Sentiment]

## Background

Applied natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. Appllied fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

Completed the following tasks:

1. [Sentiment Analysis](#1---Sentiment-Analysis)
2. [Natural Language Processing](#2---Natural-Language-Processing)
3. [Named Entity Recognition](#3---Named-Entity-Recognition)

---

## Files

(crypto_sentiment.ipynb)
(Readme)
(.env from newsapi)
---

### 1 - Sentiment Analysis

Used the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

Use descriptive statistics to answer the following questions:

> Which coin had the highest mean positive score?
>
> Which coin had the highest negative score?
>
> Which coin had the highest positive score?

### 2 - Natural Language Processing

Used NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both coins. 
#### Tokenized Text 

1. Lowercased each word.
2. Removed punctuation.
3. Removed stop words.
#### N-grams

1. Used NLTK to produce the ngrams for N = 2.
2. Listed the top 10 words for each coin.
#### Word Clouds

Generated word clouds for each coin to summarize the news for each coin.
### 3 - Named Entity Recognition

Built a named entity recognition model for both coins and visualized the tags using SpaCy.

