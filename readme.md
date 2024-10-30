# Sentiment Analysis of Reviews using LSTM and Naive Bayes Classifier

---

## Project Description
This project involves developing a model to classify reviews as positive or negative, utilizing two main approaches: an LSTM model and a Naive Bayes classifier.

### Approach 1: LSTM Model
- **Data Preprocessing**: The text data was cleaned, tokenized, and padded to ensure uniform input lengths.
- **Model Architecture**: A Sequential model was built with the following layers:
  - **Embedding Layer**: Captures word embeddings.
  - **SpatialDropout1D**: Helps prevent overfitting.
  - **LSTM Layer**: Captures the temporal relationships in the text.
- **Performance**: Achieved an accuracy of 79% on the test set.

### Approach 2: Naive Bayes Classifier
- **Data Preprocessing**: Reviews were cleaned, stemmed, and stopwords were removed.
- **Feature Extraction**: Text was transformed into a bag-of-words model using `CountVectorizer`.
- **Performance**: Achieved an accuracy of 73% on the test set.

---

