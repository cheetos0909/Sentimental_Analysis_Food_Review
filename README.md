# Sentiment Analysis with NLTK and VADER

This project performs sentiment analysis on a dataset of Amazon reviews using NLTK (Natural Language Toolkit) and VADER (Valence Aware Dictionary and sEntiment Reasoner).

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [NLTK Stuff](#nltk-stuff)
- [Sentiment Analysis with VADER](#sentiment-analysis-with-vader)
- [Results and Visualizations](#results-and-visualizations)
- [Drawbacks](#drawbacks)

## Prerequisites

Before you begin, make sure you have the following libraries installed:

- NLTK
- Matplotlib
- Seaborn
- Pandas
- Numpy
  
- SentimentIntensityAnalyzer from NLTK

You can install these libraries using `pip`, as shown in the code comments.

## Installation

Clone this repository to your local machine:

```bash
git clone <repository-url>
```

Install the required libraries using pip:

```python
pip install nltk torch matplotlib seaborn pandas numpy 
```

## Usage

1) Download the dataset to analyze and save it as 'Refined.csv' in the project directory.

2) Run the Python script to perform sentiment analysis on the dataset.

3) View the results and visualizations generated by the script.


## Data Preprocessing

The dataset is read from 'Refined.csv', and basic exploratory data analysis (EDA) is performed to understand the distribution of review scores.

## NLTK Stuff

- Tokenization of Text
- Part-of-Speech Tagging
- Named entity recognition (NER) using NLTK's chunking.

## Sentiment Analysis with VADER

Sentiment analysis is performed using the VADER sentiment analyzer. The VADER model calculates sentiment scores for each review, including compound, positive, negative, and neutral scores.

## Results and Visualizations

Visualizations of sentiment scores (compound, positive, negative, neutral) are provided, showing how sentiment relates to the Amazon star reviews.
