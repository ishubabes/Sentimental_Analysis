# Reddit Sentiment Analysis and Topic Visualization

A Python-based project to perform sentiment analysis on Reddit posts within any specified subreddit. This tool fetches recent popular posts, analyzes their sentiment using VADER, identifies key positive topics, and visualizes average sentiment scores across those topics with an intuitive spider chart.

---

## Features

- **Reddit API Integration:** Uses `praw` to connect to Reddit and retrieve posts from any public subreddit.
- **Sentiment Analysis:** Applies VADER sentiment analysis to combine post titles and selftext, scoring sentiment polarity on each post.
- **Keyword Extraction:** Identifies the most frequent and meaningful words from the top positive posts' titles to discover trending topics.
- **Topic Sentiment Categorization:** Calculates average sentiment scores for posts containing those keywords.
- **Data Visualization:** Displays a spider (radar) chart to visually represent the average sentiment for each major topic in the subreddit.
- **Top Post Listings:** Prints out top 5 most positive and top 5 most negative posts with sentiment scores and direct Reddit links.
- **Stopword Filtering:** Custom stopword removal for cleaner keyword extraction, including extra common words.

---

## Installation

Make sure you have Python 3.7+ installed. Then install dependencies with:

```bash
pip install praw vaderSentiment tabulate nltk matplotlib numpy


Bar charts comparing model accuracy across stocks and indices.
