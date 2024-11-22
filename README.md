# Email-spam-classification

This project uses Natural Language Processing (NLP) techniques to classify emails as **spam** or **ham** (non-spam).

## Dataset

The dataset used in this project is the **Email Spam Dataset**, which contains labeled emails classified as either **spam** or **ham**.

## Steps

1. **Data Preprocessing**:
   - Clean the email content by removing unnecessary characters and stop words.
   - Tokenize the text to prepare it for vectorization.

2. **Feature Extraction**:
   - Convert email content into numerical format using **TF-IDF** vectorization.

3. **Model Training**:
   - Train a **Naive Bayes** classifier on the transformed data.

4. **Model Evaluation**:
   - Evaluate the model using **precision**, **recall**, and **F1-score** metrics.



