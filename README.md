# Sentiment Analysis of Airline Customers using Tweets 

Aim to apply natural language processing techniques such as tokenization, lemmatization, stemming, parts-of-speech tagging and text parsing methods on text data from Tweets to capture customer sentiment.

You can view and run the code in Google Colab: [Link](https://colab.research.google.com/drive/1zB5F5IU3V1PLFCsBIC27ghoUbPdrC_Ir)

Sentiment Analysis Tools:
  * TextBlob
  * VADER

Achieved prediction accuracy of 82% for 0 (negative sentiment) or 1 (positive sentiment) by pre-processing text data by tuning parameters of algorithms.
Algorithms used:
  * Logistic Regression
  * K-Nearest Neighbours
  * Support Vector Machines
  * Decision Tree
  * Random Forest classifier
  * Ada Boost
  * Multinomial Naïve Bayes

|Type| | | Logistic Regression | K- Neighbors | SVC | Decision Tree | Random Forest | Ada Boost | Multinomial Naïve Bayes|
|:--:|:-:|:-:|:------------------:|:-------------:|:---:|:-------------:|:-------------:|:---------:|:----------------------:|
| Bag of Words | Model  | accuracy | 65% | 59% | 74% | 76% | 81% | 79% | 82%|
|              | negative | precision | 65% | 84% | 77% | 81% | 85% | 82% | 82%|
|              | negative | recall    | 100% | 45% | 40% | 81% | 87% | 86% | 93%|
|              | positive | precision | 0% | 46% | 74% | 66% | 75% | 72% | 83%|
|              | positive | recall | 0% | 85% | 93% | 66% | 71% | 65% | 64%|
| TF-IDF | Model | accuracy | 65% | 73% | 66% | 72% | 81% | 78% | 79%|
|        | negative | precision | 65% | 85% | 65% | 80% | 83% | 83% | 77%|
|        | negative | recall | 100% | 71% | 100% | 76% | 90% | 81% | 98%|
|        | positive | precision | 0% | 59% | 100% | 60% | 78% | 68% | 92%|
|        | positive | recall | 0% | 76% | 3% | 66% | 66% | 71% | 46%|

---
Data Source: https://data.world/crowdflower/airline-twitter-sentiment
