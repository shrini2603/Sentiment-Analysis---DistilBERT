
# Sentiment Analysis Using DistilBERT

## **Overview**
This project demonstrates how to perform sentiment analysis on Amazon product reviews using **DistilBERT**, a lightweight version of BERT, for embedding extraction and **Logistic Regression** as the final classifier.

The goal is to classify reviews as:
- **Positive** (Label: 1)
- **Negative** (Label: 0)

---

## **Dataset**
- **Source**: Amazon Product Reviews (synthetic dataset for demonstration purposes)
- **Size**: 1000 reviews
  - 500 Positive reviews
  - 500 Negative reviews
- **Format**: Each record contains:
  - `Review`: The text of the review.
  - `Sentiment`: Sentiment label (1 for Positive, 0 for Negative).

---

## **Approach**
### **1. Preprocessing**
- Tokenized the review text using **DistilBERT Tokenizer**.
- Padded and truncated sequences to ensure consistent input size.

### **2. Fine-Tuning**
- Fine-tuned **DistilB
