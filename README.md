# Sentiment Analysis Project

This project builds models to classify consumer opinions into **negative**, **neutral**, or **positive** sentiment. The following models are implemented:

- **DistilBERT** (fine-tuned transformer)
- **Logistic Regression** (TF-IDF features)
- **SVM (LinearSVC)** (TF-IDF features)

This code is part of a final project for the **TextMining** course, therefore comments and descriptions in the file are in polish language.

## Contents

1. **Data Preparation**  
   - Text preprocessing: cleaning, tokenization, stopword removal, lemmatization.
   - Class balancing using oversampling.

2. **Model Training**  
   - Logistic Regression and SVM trained on TF-IDF vectors.
   - DistilBERT fine-tuned on the processed data.

3. **Evaluation**  
   - F1-score, precision, recall, and accuracy are calculated.
   - Confusion matrices and comparisons of model performance are included.
