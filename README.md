# Unit 12—Tales from the Crypto

## Background

There's been a lot of hype in the news lately about cryptocurrency, so I wanted to pull the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

In this project, I applied natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. I then used fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

### 1 - Sentiment Analysis

Used the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

Use descriptive statistics to answer the following questions:

> Which coin had the highest mean positive score?
> ##### Bitcoin had a higher mean positive score of .059
>
> Which coin had the highest negative score?
> ##### Ethereum had a higher compound score of -.05
>
> Which coin had the highest positive score?
> ##### Bitcoin had the highest positive score of .17
>

### 2 - Natural Language Processing

In this section, I used NLTK and Python to tokenize text, find n-gram counts, and created word clouds for both coins. 

#### Tokenize

1. Lowercase each word.
2. Remove punctuation.
3. Remove stop words.

#### N-grams

1. Use NLTK to produce the ngrams for N = 2.
2. List the top 10 words for each coin.

#### Word Clouds

Finally, I generated word clouds for each coin to summarize the news for each coin.

![bitcoin](https://user-images.githubusercontent.com/98990090/170605821-b3a65a94-bba4-4ea3-90dc-dbec7c55cb77.png)

![ethereum](https://user-images.githubusercontent.com/98990090/170605828-64794b63-55b9-4b79-8db9-7a203b7ba0a5.png)

##### Interestingly, the word Bitcoin was still a standout in the Word Cloud for Ethereum, which shows Bitcoin will continue to be the baseline of what everyone compares cryptocurrency to.
