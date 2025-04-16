# Email Spam Detection Using Machine Learning

This project demonstrates a machine learning approach to classify emails as **spam** or **ham**. Using a labeled dataset, we preprocess textual data and train models to accurately predict the nature of incoming emails.

## Problem Statement

We’ve all been the recipient of spam emails before. Spam mail, or junk mail, is a type of email that is sent to a massive number of users at one time, frequently containing cryptic messages, scams, or most dangerously, phishing content.
In this Project, use Python to build an email spam detector. Then, use machine learning to train the spam detector to recognize and classify emails into spam and non-spam.

## Objective

The objective of this projrct is to develop an intelligent system that can automatically identify and filter out spam emails with high accuracy. By leveraging machine learning techniques, the project aims to analyze and learn from patterns in email content to distinguish between ham and spam messages. The ultimate goal is to enhance email security, reduce user exposure to harmful or irrelevant content, and improve overall communication efficiency, while also addressing concerns related to data privacy.

## Project Overview

This notebook walks through a machine learning pipeline that includes:

- Text preprocessing (tokenization, vectorization)
- Model training using algorithms like Multinomial Naive Bayes
- Performance evaluation using accuracy, precision, recall, and F1-score

## Technologies Used

- Python 
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

## Vizualisations

- Distribution of Spam vs Ham messages using pie chart
- WordCloud plot visualization for most used words in spam messages

## Conclusions
- Accuracy of model is 96.77% , this means the model correctly classified ~97% of the messages as either spam or ham.
- The model is excellent at identifying ham.
- Very cautious about flagging spam — no false alarms, but might let some spam slip through.
