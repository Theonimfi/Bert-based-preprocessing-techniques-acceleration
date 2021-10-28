# Bert-based-preprocessing-techniques-acceleration

This repository contains the code needed to run the experiments in the "Bert Based Evaluation of Preprocessing Techniques" paper.

The primary purpose of the paper mentioned above is to examine and compare 15 preprocessing techniques described in the literature and adjusted in four SA datasets, using the uncased Bert-base model. To accomplisht hat, we train the model with every preprocessing technique for all datasets, and then we analyze results.

## Preprocessing techniques

We use the following preprocessing techniques:

1. Stemming
2. Lemmatization
3. Lowercasing
4. Contracted words expansion
5. Emojis and Emoticons Handling
6. Repetition punctuation replacement
7. Capitalized words handling
8. Remove urls
9. Remove numbers
10. Remove stop words
11. Remove hashtags
12. Remove extra space
13. Remove punctuation
14. Remove repeated characters
15. Remove mentions

## Datasets

We used the following Sentiment Analysis Datasets:

1. [Twitter US Airline Sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)
2. [Consumer Reviews of Amazon Products]{https://www.kaggle.com/datafiniti/consumer-reviews-of-amazon-products)
3. [Automotive Products Reveiw](https://jmcauley.ucsd.edu/data/amazon/)
4. [Sentiment Self-driving Cars](https://data.world/crowdflower/sentiment-self-driving-cars)

## Bert-base model

We used the uncased Bert-base model that can be found [here](https://tfhub.dev/google/bert_uncased_L-12_H-768_A-12/1).
