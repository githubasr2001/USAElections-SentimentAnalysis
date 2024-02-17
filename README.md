# U.S. Election Sentiment Analysis

## Project Overview

This project analyzes the sentiment of tweets regarding two key figures in the U.S. election: Donald Trump and Joe Biden. Using Python, the project performs sentiment analysis on tweet datasets to categorize sentiments as positive, negative, or neutral. The analysis aims to uncover public sentiment towards each candidate and predict election outcomes based on the sentiment data.

## Features

- Data loading and preprocessing: Reads tweet data for each candidate from CSV files.
- Sentiment analysis: Utilizes TextBlob to compute sentiment polarity scores for each tweet.
- Data visualization: Generates plots to compare the sentiment distribution between the two candidates.
- Sentiment categorization: Categorizes tweets based on their sentiment polarity into positive, negative, or neutral categories.
- Predictive analysis: Speculatively predicts the election winner based on the proportion of positive to negative sentiments.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- TextBlob
- scikit-learn
- plotly

## Installation

To set up the project environment, ensure that Python 3.x is installed on your system. Then, install the required Python libraries using pip:

pip install pandas numpy matplotlib textblob scikit-learn plotly


## Usage

To run the sentiment analysis:

1. Place your dataset CSV files in the project directory.
2. Run the notebook `USA_Election_SentimentAnalysis.ipynb` using Jupyter Notebook or Google Colab.
3. Follow the steps in the notebook to load data, compute sentiment, and visualize the results.

## Dataset

The datasets used in this project, `Trumpall2.csv` and `Bidenall2.csv`, contain tweets related to Donald Trump and Joe Biden, respectively. Each tweet is analyzed to determine the sentiment polarity.

