# Machine Learning Email Spam Detection 

## Problem
Spam emails can expose users to phishing attacks, scams, and unwanted content.  
This project aims to build a **machine learning model that automatically classifies emails as spam or not spam** based on their text content.

---

## Approach
The project follows a standard NLP pipeline:

1. **Data Preprocessing**
   - Clean email text
   - Remove punctuation and stopwords
   - Normalize the text

2. **Feature Extraction**
   - Convert text data into numerical features using **TF-IDF vectorization**.

3. **Model Training**
   - Train a machine learning model to classify emails.

4. **Model Evaluation**
   - Evaluate the model using accuracy and classification metrics.

---

## Model
- **Logistic Regression**

Logistic Regression is widely used for text classification problems because it performs well with high-dimensional features such as TF-IDF vectors.

---

## Results
The trained model successfully classifies emails into **Spam** and **Not Spam**.

**Accuracy:** 98.27%

---

## Technologies Used
- Python
- Pandas
- Scikit-learn
- NLTK
- Jupyter Notebook

---

## Author
**Mahmoud Eltabiey**
