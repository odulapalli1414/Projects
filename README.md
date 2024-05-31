# IMDB Movie Review Sentiment Analysis

## Overview
This project focuses on sentiment analysis of movie reviews from the IMDB dataset. The dataset contains movie reviews along with their sentiment labels (positive or negative). The goal is to train machine learning models to accurately classify the sentiment of a given review as either positive or negative.

## Project Structure
- **notebooks**: Jupyter notebooks used for data preprocessing, model training, and evaluation.
- **README.md**: Overview of the project, setup instructions, and usage guidelines.

## Data Source
The dataset used in this project is available on Kaggle at [Sentiment Analysis of IMDB Movie Reviews](https://www.kaggle.com/code/lakshmi25npathi/sentiment-analysis-of-imdb-movie-reviews/input).


## Setup Instructions
1. Clone the repository: `git clone <repository-url>`
2. Download the dataset from Kaggle link provided above.
3. Navigate to the project directory: `cd imdb-sentiment-analysis`
4. Install dependencies
5. Run the Jupyter notebooks in the `notebooks` directory to explore the data, preprocess it, train models, and evaluate their performance.

## Usage
1. **Data Preprocessing**: The provided notebooks cover various preprocessing steps such as removing HTML tags, special characters, stopwords, and stemming.
2. **Model Training**: Train machine learning models using bag-of-words (BOW) and TF-IDF features. Models such as Logistic Regression, Linear SVM, and Multinomial Naive Bayes are implemented and evaluated.
3. **Model Evaluation**: Evaluate the trained models using accuracy score, classification report, and confusion matrix. Word clouds are also generated to visualize frequent words in positive and negative reviews.

## Contributions
Contributions to this project are welcome. If you have any suggestions for improvements or new features, please feel free to open an issue or submit a pull request.
