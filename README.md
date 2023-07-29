# Suicidal_Ideation_Detection
This project aims to develop a system that can detect suicidal ideation on Twitter using Natural Language Processing (NLP) and Machine Learning (ML) models, including Logistic Regression, Support Vector Machines (SVM), Random Forest (RF), Multinomial Naive Bayes (MNB), Ensemble Learning, AdaBoost, Long Short-Term Memory (LSTM), Gated Recurrent Unit (GRU), Convolutional Neural Networks (CNN), and Bidirectional Encoder Representations from Transformers (BERT). This project aims to identify individuals who may be at risk of suicide and contribute to suicide prevention efforts.

**Dataset:
**
I've used the Twitter Suicide Dataset, which contains Tweets from individuals who have experienced suicidal thoughts and ideations. 
The dataset includes more than 1787 Tweets and comments, and it has been labeled as either indicating suicidal ideation or not.

**Data Preprocessing:**
As part of the data preprocessing phase, First I converted Tweets to lower case then cleaned and filtered the text by removing URLs, stop words, and special characters.
Next, I tokenized the text and performed stemming and lemmatization to reduce the words to their base form. This step helped in reducing the dimensionality of the data and improved the efficiency of the models.

**Feature Extraction:
**
For feature extraction, I used the Term Frequency-Inverse Document Frequency (TF-IDF) technique. Additionally, I also experimented with custom embeddings to capture semantic meaning and reduce the dimensionality of the data.
These techniques helped in representing the text in a numerical format that could be used by the models to make predictions.

Machine Learning Models:
During the experimentation phase, I trained several ML models including Logistic Regression, Support Vector Machines (SVM), Random Forest (RF), Multinomial Naive Bayes (MNB), Ensemble Learning, and AdaBoost. These models were used to make predictions on the test set and identify individuals who may be at risk of suicide.
