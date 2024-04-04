# Text Analysis on Great Expectations

This repository contains a Python project for performing text analysis on the novel "Great Expectations" by Charles Dickens. The project includes various tasks such as pulling text data, cleaning the data, creating a word cloud, analyzing word frequency, performing sentiment analysis using Vader, building a corpus and dictionary for topic modeling, and conducting topic modeling using Latent Dirichlet Allocation (LDA).

## Getting Started

To use or contribute to this project, follow the instructions below:

1. Clone the repository to your local machine.
2. Make sure you have the required libraries installed, including NLTK, Gensim, wordcloud, pandas, PIL, numpy, and matplotlib.
3. Uncomment the necessary lines to download additional NLTK resources if they are not already downloaded.
4. Place the "great_expectations.txt" file in the same directory as the project files. This file should contain the text of the novel "Great Expectations".
5. If you want to use a custom mask for the word cloud, replace the "man_in_top_hat.jpeg" file with your own image file. Otherwise, the default mask will be used.
6. Run the Python script to execute the text analysis tasks.

## Functionality

The project provides the following functionality:

1. **Pulling text data**: The script reads the "great_expectations.txt" file and extracts the content.
2. **Cleaning text data**: The text data is cleaned by converting it to lowercase, removing numbers and alphanumeric words, tokenizing the data, removing stopwords and short words, and splitting the data into sentences.
3. **Creating a Word Cloud**: A word cloud is generated to visualize the most frequent words in the text data. The word cloud can be customized by modifying the parameters.
4. **Improving the word cloud**: An advanced word cloud is created with a custom mask and color scheme.
5. **Analyzing word frequency**: The script calculates the frequency distribution of words and visualizes the 50 most frequent words.
6. **Performing Vader sentiment analysis**: Vader sentiment analysis is applied to the sentences in the text data to determine the sentiment (positive, negative, or neutral) of each sentence. The overall sentiment distribution is visualized.
7. **Building a Corpus and a Dictionary for Topic Modeling**: The text data is preprocessed by removing numbers, tokenizing, lemmatizing, removing stopwords, and removing short words. A dictionary and corpus are created for topic modeling.
8. **Performing Topic Modeling**: Latent Dirichlet Allocation (LDA) is used to perform topic modeling on the text data. The optimal number of topics is determined, and the resulting topics are displayed.

## Requirements

- Python 3.12.2
- NLTK
- Gensim
- wordcloud
- pandas
- PIL
- numpy
- matplotlib