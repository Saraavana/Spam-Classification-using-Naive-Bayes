# Spam Classification using Naive Bayes

## Introduction

I have implemented a Spam Classification system using the Naive Bayes algorithm. The dataset consists of two columns:

1. **Category:** This column indicates whether the email is categorized as "Spam" or "Ham" (not spam).
2. **Message:** This column contains the actual text of the email.

The dataset used for this purpose consists of a total of 5,572 emails.

## Naive Bayes Algorithm

Naive Bayes is a simple yet powerful algorithm, it is based on Bayes' theorem and assumes that features are conditionally independent of each other given the class label. Despite its simplifying assumption, Naive Bayes has proven to be effective in many real-world applications, including text classification.

The Naive Bayes algorithm calculates the probability of a particular class given the observed features. In the case of spam classification, the algorithm learns from the provided dataset, estimating the probability that an email belongs to the "Spam" or "Ham" class based on the words frequency in the email's text. It is computationally efficient to handle large datasets. And it is robust to feature interactions and provides faster training and predictions.

This implementation of the Naive Bayes algorithm for spam classification has yielded an impressive accuracy of 98% for classifying spam messages from emails. This high accuracy demonstrates the effectiveness of the Naive Bayes algorithm in distinguishing between spam and non-spam emails based on the text content alone.

