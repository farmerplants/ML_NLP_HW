# UMN Fintech -- Machine Learning &amp; Classification Homework
## The solutions can be found in the Resources and Solutions folder:
### Crypto Sentiment: https://github.com/farmerplants/ML_NLP_HW/blob/main/Resources%20and%20Solutions/crypto_sentiment.ipynb

## Homework Background:
### There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin. In this assignment, you will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. You will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

### Complete the following tasks:
#### 1. Sentiment Analysis
#### 2. Natural Language Processing (NLP)
#### 3. Named Entity Recognition (NER)

## Homework Instructions:
### 1 - Sentiment Analysis: Use https://newsapi.org/ to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin. Use descriptive statistics to answer the following questions:
#### - Which coin had the highest mean positive score?
#### - Which coin had the highest negative score?
#### - Which coin had the highest positive score?

### 2 - Natural Language Processing: In this section, you will use NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both coins. 
### Tokenizing - be sure to:
#### 1. Lowercase each word.
#### 2. Remove punctuation.
#### 3. Remove stop words.
### N-grams: Next, look at the ngrams and word frequency for each coin.
#### 1. Use NLTK to produce the ngrams for N = 2.
#### 2. List the top 10 words for each coin.
### Word Clouds: Finally, generate word clouds for each coin to summarize the news for each coin.

### 3 - Named Entity Recognition: In this section, you will build a named entity recognition model for both coins and visualize the tags using SpaCy.


## Conclusions:
### Sentiment Analysis:
#### - Which coin had the highest mean positive score? - Ethereum (0.0788) had a higher score than Bitcoin (0.0477).
#### - Which coin had the highest negative score? - Ethereum's max score (0.834) had a higher score than Bitcoin (0.637).
#### - Which coin had the highest positive score? - Ethereum had a higher positive score (0.249) than Bitcoin (0.152).
