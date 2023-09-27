
# Text Analysis Project
# Overview
This repository contains a text analysis project that focuses on classifying stories in Hebrew (written by different authors) into two categories: male-authored and female-authored. The project utilizes machine learning techniques to achieve this classification task.

# Project Contributors
[Orel Israel (GitHub: IsrOrel)]

[Amit Pompas (GitHub: AmidelEst)]

# Data Preparation
The project starts with the following steps for data preparation:

# Data Exploration:
Initially, we explored the dataset to understand its structure. We noticed an imbalance between male and female-authored stories, so we decided to downsample the male-authored stories to create a balanced dataset.

# Data Cleaning:
We cleaned the text data by retaining only Hebrew letters and removing all punctuation and non-alphabetic characters. This step helped standardize the text and remove noise from the data.

# Tokenization:
Tokenization is performed to split the text into individual words or tokens, making it suitable for machine learning analysis.

# Feature Engineering
To represent the text data in a format suitable for machine learning models, we used TF-IDF (Term Frequency-Inverse Document Frequency) vectorization. This technique converts the text into numerical features that can be used for classification.

# Model Selection
We experimented with several machine learning classifiers to determine which one performs best for the task of classifying male and female-authored stories. The following classifiers were considered:

Linear Support Vector Classifier (LinearSVC)
Stochastic Gradient Descent Classifier (SGDClassifier)
Multinomial Naive Bayes (MultinomialNB)
Gaussian Naive Bayes (GaussianNB)
Decision Tree Classifier
K-Nearest Neighbors (KNeighbors)
The goal was to identify the model with the highest classification accuracy on the given dataset.

# Conclusion
This project demonstrates the process of text analysis and classification of stories based on author's gender. By balancing the dataset, cleaning and tokenizing the text, and using TF-IDF features, we were able to train and evaluate multiple machine-learning models to make authorship predictions.

