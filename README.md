# Sentiment Analysis Practice Project

## Overview

This practice project performs sentiment analysis on top headlines from UK news sources and Reddit posts from the `unitedkingdom` subreddit. It uses Natural Language Processing (NLP) and Latent Dirichlet Allocation (LDA) for topic modeling. The project aims to visualize the overlap of topics between the two platforms through Venn diagrams.

## Technologies Used

- Python 3.x
- PRAW (Python Reddit API Wrapper)
- TextBlob
- NLTK (Natural Language Toolkit)
- spaCy
- scikit-learn
- matplotlib-venn

## Features

- **Data Collection**: Gathers top headlines from UK news and Reddit posts.
  
- **Text Preprocessing**: Tokenizes, lemmatizes, and removes stopwords from the text.

- **Topic Modeling**: Utilizes LDA to model topics and automatically labels them based on frequent terms.

- **Visualization**: Creates Venn diagrams to show topic overlap between UK news and Reddit posts.
