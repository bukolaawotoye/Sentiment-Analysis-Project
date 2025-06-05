# Sentiment-Analysis-Project
Sentiment Analysis on Twitter Data for Government Policy Feedback
This project leverages Natural Language Processing (NLP) techniques to analyze public sentiment in tweets regarding government policies. The goal is to provide actionable insights by determining whether citizens' reactions are positive, negative, or neutral, thereby helping government agencies better understand public opinion.
Table of Contents
- Project Overview
- Features
- Installation
- Usage
- Project Structure
- Results
- Future Work
- License
Project Overview
In this project, we:
- Clean and Preprocess Data: Remove noise such as special characters, single-character tokens, and multiple spaces. Convert text to lowercase.
- Sentiment Analysis: Use TextBlob to calculate polarity and subjectivity scores of tweets.
- Data Exploration: Categorize tweets as positive, negative, or neutral. Identify the most polar, most subjective, and most objective examples.
- Feature Engineering and Vectorization: Tokenize text using NLTK’s TweetTokenizer and transform it into numerical features using CountVectorizer and TfidfVectorizer.
- Classification: Build and evaluate machine learning models (Multinomial Naive Bayes & Random Forest) to classify tweets by their sentiment.
- Visualization and Reporting: Generate outputs to understand the distribution and characteristics of sentiment across the dataset, providing insights into citizen responses to policy changes.
Features
- Data Cleaning: Robust preprocessing via regular expressions to remove unwanted characters and standardize text.
- Sentiment Scoring: Calculation of polarity and subjectivity using TextBlob.
- Model Training: Comparison of classification models with multiple metrics.
- Interpretability: Clear mapping of sentiment scores and identification of extreme cases (most positive, negative, subjective, objective).
- Actionable Insights: Analysis of public opinion that can inform government decisions.
