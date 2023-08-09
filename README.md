# Sentiment Analysis with BERT

## Introduction
Sentiment analysis, also known as opinion mining, involves categorizing sentiments in text as positive, negative, or neutral. In this project, I have explored various Natural Language Processing (NLP) techniques to improve sentiment classification, with a particular focus on social media data.

## Objectives
- Evaluate NLP techniques for sentiment analysis
- Improve sentiment classification accuracy on social media text
- Understand and evaluate public opinion and reactions through sentiment analysis
- Advance sentiment analysis methods for social media platforms

## How to Solve It
1. Data Exploration
2. Data Preparation
3. Model Selection
4. Model Performance

### Data Exploration
#### Training Data
The training dataset includes text ID, original tweet text, selected text representing sentiment, and sentiment label (positive/negative/neutral).

#### Test Data
The test dataset contains text ID, original tweet text, and corresponding selected text.

#### Word Clouds
Visualizing positive, negative, and neutral sentiment word clouds reveals insights. Positive words like "love" and "good" dominate positive sentiment, while negative words like "sad" and "miss" characterize the negative sentiment word cloud.

#### Sentiment Distribution
The dataset presents comparable counts between positive and negative sentiments, with neutral sentiment exhibiting a higher count.

#### Text Length Distribution
Text lengths display similarities across different tweet categories.

#### Null Values and Duplicates
The dataset is complete and free of duplicates.

### Data Preparation
I performed text preprocessing using NLP techniques, including converting to lowercase, removing punctuation, stopwords, and stemming.

#### TF-IDF Calculation
TF-IDF (Term Frequency-Inverse Document Frequency) identifies significant words within each text based on their frequency and rarity.

#### Vectorization
Text vectorization transforms raw text into numerical representations suitable for machine learning.

### Model Selection
I explored alternative models like standard logistic regression and SVMs. However, BERT stood out due to its contextual understanding of language.

#### BERT Tokenization
I employed the BERT tokenizer to prepare input texts for the BERT model. Tokenized input is converted into numerical IDs.

#### BERT Model
BERT generates contextualized token representations. Fine-tuning BERT on sentiment analysis tasks enhances its performance.

#### Model Evaluation
I assessed models using the F1 score, which balances precision and recall. BERT with logistic regression achieved the highest F1 score of 0.8749.


Feel free to explore the repository for detailed code and insights into this sentiment analysis project. If you have any questions or feedback, don't hesitate to reach out!
