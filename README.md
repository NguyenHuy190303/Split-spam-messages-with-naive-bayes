# Spam Message Classification using Naive Bayes

## Project Overview
This project involves building a text classification model to detect spam messages using the Naive Bayes algorithm. Text classification is a common task in Machine Learning and Natural Language Processing (NLP), with applications such as detecting negative comments online, identifying positive product reviews, and filtering out unwanted messages.

## Project Structure
- **Introduction**: Overview of the text classification task, with a focus on spam detection.
- **Data Preparation**: Steps for loading and preprocessing the dataset.
- **Model Training**: Implementation of the Naive Bayes classifier to distinguish between spam and non-spam messages.
- **Evaluation**: Assessing the model's performance using accuracy metrics.
- **Prediction**: Using the trained model to classify new messages.

## Dataset
The dataset consists of labeled messages, classified into two categories: 
- `ham`: Non-spam messages that are generally expected by the recipient.
- `spam`: Unwanted messages, often for advertising or fraudulent purposes.

## Installation
The project is implemented in Python, and the following libraries are required:
- `nltk` (Natural Language Toolkit): For text processing.
- `pandas`: For data manipulation.
- `numpy`: For numerical operations.
- `scikit-learn`: For building and evaluating the machine learning model.

To install these dependencies, run:
```bash
pip install nltk pandas numpy scikit-learn
