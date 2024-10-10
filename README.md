# Project Title:SMS Detection Classifier

## Overview
This project aims to classify SMS messages as spam or not spam using various text preprocessing techniques and machine learning algorithms. The dataset used contains labeled SMS messages.
This project involves end-to-end data processing, analysis, and model building. The following steps were undertaken:

## 1. Data Cleaning
- Handled missing values
- Standardized data formats
- Removed duplicates and irrelevant data

## 2. Exploratory Data Analysis (EDA)
- Generated visualizations to understand data patterns and relationships
- Identified correlations and significant features impacting the outcome variable

## 3. Text Preprocessing
Performed several operations on textual data:
- **Lowercase Conversion**: All text was converted to lowercase for uniformity
- **Tokenization**: Split the text into individual tokens (words)
- **Special Character Removal**: Removed unwanted characters like punctuation, numbers, etc.
- **Stop Words Removal**: Filtered out common words that do not contribute to meaning (e.g., 'the', 'is', etc.)
- **Stemming**: Reduced words to their root forms
- **WordCloud**: Generated a word cloud for visual representation of common words

## 4. Vectorization
Transformed text data into numerical representations using:
- **Bag of Words (BoW)**
- **TF-IDF Vectorizer**

## 5. Model Building
Implemented different versions of Naive Bayes for classification:
- **Multinomial Naive Bayes**
- **Bernoulli Naive Bayes**
- **Gaussian Naive Bayes**

## 6. Evaluation
Evaluated the models using:
- Accuracy
- Precision
- Confusion Matrix

## 7. Model Improvement
Performed scaling,hyperparameter tuning and tried different preprocessing techniques to enhance model performance.

## Conclusion
Summarized findings and presented the final performance of the best model.
