📊 Bitcoin & Crypto News Text Analysis

This repository contains a complete workflow for performing text analytics on news articles related to Bitcoin and cryptocurrencies.
The analysis covers preprocessing, sentiment analysis, topic modeling (using NMF), visualization, and n-gram frequency extraction.

🚀 Project Overview

The goal of this project is to extract insights from crypto-related news articles and understand:

Sentiment trends (positive, negative, neutral)

Dominant topics in the news

Most frequent bigrams and trigrams

Word importance & relationships using bar charts and word clouds

This provides a foundation for crypto market sentiment research, media monitoring, and investor behavior analysis.

📂 Dataset

Input: An Excel file containing Bitcoin/Crypto-related news.

Example file name: Play_Store.xlsx

Column of interest: text (news content).

⚠️ Replace Play_Store.xlsx with your actual dataset file.

🛠️ Tech Stack

Python 🐍

Libraries:

pandas – data handling

nltk – text preprocessing & stopwords removal

textblob – sentiment analysis

scikit-learn – TF-IDF + NMF topic modeling

matplotlib & seaborn – visualizations

wordcloud – word cloud generation

collections.Counter – bigram & trigram analysis

🔄 Workflow

Data Cleaning & Preprocessing

Remove missing rows

Convert text to lowercase

Remove special characters

Remove stopwords

Sentiment Analysis

Sentiment polarity scores using TextBlob

Categorization into Positive, Negative, Neutral

Pie chart visualization of sentiment distribution

Topic Modeling (NMF)

TF-IDF vectorization

Non-negative Matrix Factorization (NMF) for topic extraction

Top 10 keywords per topic

Bar charts & Word Clouds for visualization

N-gram Analysis

Generate bigrams & trigrams

Frequency distribution of top 20 bigrams/trigrams

📊 Example Outputs

✅ Sentiment distribution pie chart

✅ Top words in each topic (bar charts)

✅ Word clouds for each topic

✅ Top bigrams & trigrams with frequencies

📁 Results

Excel Output: sentiment_analysis_results.xlsx (includes processed text, sentiment score, sentiment category, and assigned topic).

Plots & Word Clouds: Displayed inline with the notebook/script.
