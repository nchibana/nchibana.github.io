---
layout: post
title: Can machine learning models accurately detect hate speech?
subtitle: A logistic regression model with 86% accuracy
bigimg: /img/path.jpg
tags: [books, test]
---

As an aspiring data science, I created a classifier to correctly identify hateful or offensive speech on Twitter. You can check it out for yourself [here](https://nchibana-twitter-hate-speech.herokuapp.com/predictions).

The model used to make these predictions was trained on a combination of two labeled datasets, with more than 100,000 tweets.

56 percent of them were labeled “Normal, 39 percent as “Offensive”, and 5 percent as “Hateful.” Of those categorized as hateful, these words to the right were the most commonly found in the data set, not counting stopwords.

I’ll click here to get a few predictions. I am going to use a few randomly selected tweets to see the results it gives us.

The first one uses several words that would be considered insulting or hateful, so the classifier labels it as hateful. You can also see here the predicted probabilities of the three classes.

The second one doesn’t include insults or strong adjectives, so it is categorized as normal.

The multiclass classifier has an accuracy score of 86%, a precision score of 90% for normal speech, but only 33% precision and recall for hateful speech detection.

This is probably due to the existence of class imbalance, as only 5% of the tweets in the dataset were labeled hateful. 

If we reconfigure this as a binary classifier, then the accuracy of the model increases to 90%, with 91% precision and 87% recall.

As an example of a misclassified tweet, this post by Donald Trump was labeled as "offensive" by the model, even though it would not be classified as such by human labelers.

Some shorter tweets tend to be misclassified as hateful because the number of terms is one of the most important features according to the coefficients of the logistic regression model used, along with sentiment scores and number of mentions.

The large area under the ROC curve for the binary version of this classifier reveals that it can distinguish accurately between hateful/offensive tweets and normal ones.
