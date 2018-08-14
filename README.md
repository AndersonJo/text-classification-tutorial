# Text Classification Tutorial

This repository uses probablistic models as tutorials and have the following contents. 

1. [Naive Bayes Explained](naive-bayes-explained.ipynb)
2. [Spam Filtering with Naive Bayes](spam-filtering-with-naive-bayes.ipynb)
3. [20 News Classification](20-news-classification.ipynb)

## Preprocessing Methods

1. Word Frequency based vectorization
2. TF-IDF


## Models

I used the following models. 

1. Naive Bayes
2. Logistic Regression
3. Support Vector Machine (Linear)
4. Deep Learning (Fully-Connected Layers)


## Accuracy

| Data  | Preprocessing | Model | Precision | Recall | F1-Score |
|:------|:--------------|:------|:----------|:-------|:---------|
| Spam Filtering | Word frequency vectorization | Naive Bayes | 0.97 | 0.97 | 0.96 |
| Spam Filtering | Word frequency vectorization | Logistic Regression | 0.95 | 0.95 | 0.95 |
| 20 News | Word frequency vectorization | Naive Bayes | 0.83 | 0.82 | 0.81 |
| 20 News | Word frequency vectorization | SVM (Linear) | 0.85 | 0.85 | 0.85 |
| 20 News | Word frequency vectorization | SVM (Linear) | 0.85 | 0.85 | 0.85 |
| 20 News | Word frequency vectorization | Deep Learning (FC Network) | 0.84 | 0.83 | 0.83 |

