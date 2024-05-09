# Sentiment Analysis on IMDB Movie Reviews

## Table of Contents

1. [Abstract](#abstract)
2. [Dataset](#dataset)
3. [Method](#method)
4. [Results](#results)
5. [Discussion](#discussion)

## Abstract
This report presents sentiment classification on the IMDB movie review dataset using machine learning techniques to predict positive or negative sentiment based on textual content.

## Dataset
The [IMDB movie review dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) from Kaggle was used, containing movie reviews labeled as positive or negative. Data preprocessing included tokenization, stop word removal, and lemmatization.

## Method
1. Data Preprocessing
2. Feature Extraction (TF-IDF vectorization)
3. Feature Engineering ('One Hot Encoded' feature based on predefined positive/negative words)
4. Data Splitting (80:20 train:test split)
5. Model Training (Logistic Regression, Random Forest Classifier)
6. Hyperparameter Tuning (Grid search)
7. Model Evaluation (Accuracy, Precision, Recall, F1-score)

## Results
- Logistic Regression (optimal C=3.5): Accuracy=0.8816, Precision=0.8745, Recall=0.8932, F1=0.8838
- Random Forest Classifier: Lower performance than Logistic Regression
<p align="center">
  <img src="https://github.com/AaranP/IMDB_Review_Sentiment/assets/66931430/a57f2a72-0b92-4987-8f41-0bbf9856dcd0" alt="Screenshot 2024-05-05 152247"><br>
  <em>Figure 1: Comparison of tuned Logistic regression model with Random Forest classifier</em>
</p>


## Discussion
- Logistic Regression outperformed Random Forest Classifier
- Future work: Advanced NLP techniques (word embeddings, transformers), ensemble methods, multi-class classification or sentiment intensity prediction

