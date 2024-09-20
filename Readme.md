# Intensity Analysis

## Project Overview

The "Intensity Analysis" project aims to analyze and predict emotions in text, such as happiness, sadness, or anger. With the rise of online reviews and social media, it's important for businesses to understand how people feel in their messages.

This project develops a system that uses Natural Language Processing (NLP) and machine learning models, specifically Support Vector Machines (SVM) or a Voting Classifier, to identify emotions and their intensity in text.

## Project Steps

1. Data Cleaning: The text data is cleaned to remove special characters and make all text lowercase.
2. Feature Extraction: Features are extracted from the text using TF-IDF vectorization.
3. Model Selection and Training:
   - Support Vector Machine (SVM): Trained and evaluated to classify emotions in the text.
   - Voting Classifier: An ensemble model combining multiple classifiers to enhance prediction accuracy.
4. Performance Evaluation: Both models were evaluated based on accuracy and other performance metrics.

## Models

- **Support Vector Machine (SVM)**: Achieved an accuracy of 79.17%.
- **Voting Classifier**: Achieved an accuracy of 80.64%.

## Requirements

- Python 3.x
- pandas
- scikit-learn
- joblib
- imbalanced-learn
- nltk

## Installation

To install the required packages, use the following command:

```bash
pip install pandas scikit-learn joblib imbalanced-learn nltk

Usage
Prepare the Data: Ensure that happiness.csv, angriness.csv, and sadness.csv are in the same directory as the code.
Run the Code: Execute the Jupyter notebook or Python script to train the models and evaluate their performance.
Model Files: The trained models and vectorizers are saved as .pkl files in the models directory.

Model Files
models/svm_model.pkl: Trained Support Vector Machine model.
models/voting_model.pkl: Trained Voting Classifier model.

Future Work
Experiment with more advanced models and techniques to further improve accuracy.
Explore additional features or data sources to enhance the emotional analysis.

Conclusion
This project provides a reliable tool for real-time emotional analysis of text, leveraging advanced NLP and machine learning techniques to deliver accurate predictions of emotions.
