# -NLP---Emotion_Classification_in_Text: Formative Assessment

# Overview

This project aims to classify text data into different emotions (e.g., anger, fear, joy) using Natural Language Processing (NLP) techniques and machine learning models. It involves preprocessing raw text data, extracting meaningful features, training classification models, and evaluating their performance.

# Features
_______

## Data Preprocessing:
  
* Text cleaning (lowercasing, punctuation removal, stopword removal)
  
* Tokenization
  
* Lemmatization

## Feature Extraction:
  
* Bag of Words (BoW) representation using CountVectorizer

##Model Training:

* Naive Bayes
  
* Support Vector Machine (SVM)
  
## Evaluation:

* Accuracy and F1 Score

* Detailed classification report for model comparison

### Dataset

* The dataset contains text comments labeled with emotions (anger, fear, joy). Each text comment is processed and transformed into numerical features for model training.

# Results

Model |	Accuracy | F1 Score

Naive Bayes |	89.13% |	89.13%

Support Vector Machine |	91.66% |	91.63%


**Best Model: Support Vector Machine (SVM)**

# Conclusion

* **Naive Bayes:**  Simple and fast with decent performance, making it suitable for lightweight applications.
  
* **SVM:**  Outperformed Naive Bayes, making it the preferred choice for emotion classification tasks requiring higher accuracy.
  
## Future Work

* Experiment with advanced feature extraction techniques like TF-IDF.
  
* Incorporate deep learning models such as LSTMs or BERT for improved classification.
  
* Add more emotions to enhance the dataset's complexity.
