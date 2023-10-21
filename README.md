# Sentiment Analysis on Twitter Data

## Overview

This Git project is a Python-based sentiment analysis application that analyzes sentiments in Twitter data. Sentiment analysis, also known as opinion mining, is a natural language processing (NLP) technique used to determine the sentiment or emotional tone expressed in textual data, in this case, Twitter tweets. The project involves preprocessing the data, training various machine learning models, and visualizing the results.

## Data Collection

**Initial Scraper Attempt**: The project initially attempted to scrape Twitter data directly from the Twitter API. However, due to limitations in the Twitter API, this approach was not successful.

**Kaggle Dataset**: To overcome the data collection challenges, the project used a Kaggle dataset containing 1.6 million tweets. This dataset served as the primary data source for the sentiment analysis.

## Key Features

**Data Preprocessing**: The project includes data preprocessing steps to clean and prepare the Twitter data for analysis. It involves tasks such as lowercasing, tokenization, stop word removal, punctuation removal, and stemming.

**Machine Learning Models**: The sentiment analysis employs machine learning models, including Logistic Regression, Naive Bayes, K-Nearest Neighbors (KNN), and Support Vector Classification (SVC) to predict sentiment labels (positive or negative) based on the processed text.

**Visualization**: The project uses Matplotlib and Seaborn for data visualization. It includes visualizations for confusion matrices and model accuracies.

**Dataset**: The project uses a Twitter dataset with sentiment labels (0 for negative and 4 for positive) and tweet text.
Getting Started

## To get started with this project, follow these steps:

Clone this Git repository to your local machine.
Ensure you have the required Python libraries and dependencies installed, including pandas, numpy, scikit-learn, Matplotlib, Seaborn, and NLTK (Natural Language Toolkit).
Run the provided Jupyter Notebook to execute the code and perform sentiment analysis on Twitter data.
Usage

The Jupyter Notebook provided in this repository offers a step-by-step guide to perform sentiment analysis. You can use this project to analyze Twitter data and gain insights into the sentiments expressed in the tweets.

## Contributions

Contributions to this project are welcome. You can submit issues or pull requests to enhance the functionality, add new features, or improve existing code.

## License

This project is open-source and available under the MIT License. You are free to use, modify, and distribute the code according to the terms of the license.
