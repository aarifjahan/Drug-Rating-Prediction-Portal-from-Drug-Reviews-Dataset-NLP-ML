# Drug-Rating-Prediction-Portal-from-Drug-Reviews-Dataset-NLP-ML
NLP techniques such as named entity recognition, sentiment analysis, topic modeling, text classification with Python to predict sentiment and rating of drug from user reviews.

## Background
In this project, the primary goal is to conduct analysis to determine how prescription drugs were rated by users based on the language of their reviews. 

The analysis includes use of NLP and ML techniques in data cleaning and preprocessing, feature extraction and engineering, and data modeling. 

## Dataset Description
The data contains patient reviews on specific drugs along with related conditions and a 10-star patient rating system reflecting overall patient satisfaction. The data was retrieved by crawling online pharmaceutical sites and later published in a study on sentiment analysis of drug experience over multiple facts including effectiveness and side effects of these drugs.

## Analytical Methods
*Text Classification* to classify raw text reviews into negative or not negative reviews

*Topic Modeling* to discover latent semantics within the raw text reviews

## Evaluation Metrics
Primary Metric - Area Under the Receiver Operating Characteristic Curve (AUC)

Seconday Metric - Accuracy, Precision, Recall, F1-Score

## Feature Generation Methods
Bag Of Words (BoW)

Term Frequency-Inverse Document Frequency (TF-IDF)

Word2Vec Embeddings

## Machine Learning Classifier Methods
Logistic Regression

Naive-Bayes

Random Forest

Gradient Boosting

## Project Files

Project_jnb_text_classification.ipynb - Contains python code used for text classification using the various ML classifiers mentioned above
Project_jnb_topic_modeling.ipynb - Contains pythong code used for applying topic modeling method
Project Report.pdf - Detailed report for the project

-- Aarif M Jahan -- Dec 12, 2021
