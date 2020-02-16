# Wrangle and analyze WeRateDogs twitter account

## Introduction
WeRateDogs is a twitter account that was formed four years ago and now has more than 7 million followers. The main purpose of this project
is to showcase the data wrangling undertaken in order to be able to analyse the account data accurately.
The complete data is gathered in 3 different ways:
- a manually downloaded csv file of the WeRateDogs twitter archive
- tweet image predictions of dog breed type had to be downloaded programmatically using the requests library and a corresponding url
- use Tweepy to query the Twitter API for each tweet which is stored in JSON format

Once the gathered data was assessed and then cleaned, it was used to look at some key important insights with regards to this twitter 
account such as whether higher dog ratings are associated with more likes or not or if the length of a tweet is associated with more likes 
or not. We will also be able to see what the most common breed of dogs that are tweeted are and also which tweets had the most liked and 
most retweeted tweets.

## Technologies
Python 2.7 or 3.6
