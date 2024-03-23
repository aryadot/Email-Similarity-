
---

# Email Classification with Naive Bayes

This project implements a Naive Bayes classifier to classify emails into different categories based on their content. Specifically, it focuses on distinguishing between baseball and hockey-related emails using the 20 Newsgroups dataset provided by scikit-learn.

## Project Overview

The goal of this project is to demonstrate the effectiveness of a Naive Bayes classifier in categorizing emails into relevant topics. By training the classifier on a dataset containing emails from the categories of 'rec.sport.baseball' and 'rec.sport.hockey', we aim to predict the category of new unseen emails accurately.

## Features

- Utilization of scikit-learn's `fetch_20newsgroups` dataset for email classification.
- Preprocessing of text data using CountVectorizer for feature extraction.
- Implementation of a Multinomial Naive Bayes classifier for classification tasks.
- Evaluation of classifier performance using accuracy metrics.

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x
- scikit-learn library (`pip install scikit-learn`)

## Installation and Setup

1. Clone the repository or download the source code to your local machine.
2. Ensure you have the required dependencies installed.
3. Run the main script (`email_classification.py`) using Python.

## Usage

1. Open the `email_classification.py` script in your preferred Python environment.
2. Follow the instructions provided in the script comments to load the dataset, preprocess the data, train the Naive Bayes classifier, and evaluate its performance.
3. Experiment with different category combinations and classifier parameters to observe changes in classification accuracy.
4. Analyze the results and interpret the classifier's performance.

## Project Structure

The project directory contains the following files:

- `email_classification.py`: Main Python script for data loading, preprocessing, training, and evaluation.
- `README.md`: Documentation file providing project overview, setup instructions, and usage guidelines.

## License

Distributed under the MIT License. See `LICENSE` for more information.

