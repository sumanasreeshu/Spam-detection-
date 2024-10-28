# **Spam Detection Analysis**
**Project Overview**

This project develops a spam detection model capable of accurately sorting messages as either spam or non-spam. The model leverages machine learning techniques to automate spam filtering, an essential function for managing modern communication platforms.

**Skills and Techniques**

- Text Preprocessing: Cleaned and prepared the text data, removing punctuation, special characters, and irrelevant words. The processed text was then tokenized and vectorized using TF-IDF (Term Frequency-Inverse Document Frequency) to highlight important terms.
- Feature Engineering: Leveraged n-grams (specifically bigrams) and TF-IDF weighting to capture word combinations frequently found in spam messages. These engineered features enhanced the model’s ability to identify subtle patterns in spam content.
**Model Selection and Comparison:**

- Tested multiple classifiers, including a Dummy Classifier as a baseline, Logistic Regression, Naive Bayes, and Support Vector Machine (SVM).
- Based on evaluation metrics, Logistic Regression provided a strong balance between accuracy and computational efficiency, making it the final model choice.
Data Exploration
- Class Distribution: The dataset contains 5,169 entries, with approximately 86% classified as non-spam ("ham") and 14% as spam, indicating a slight class imbalance.
- Message Length: Analysis showed that spam messages often had shorter lengths, focusing on specific keywords, while non-spam messages had more variation in length.
**Impactful Results**

The final model achieved an accuracy of 97.87% with a precision of 97% for spam detection and an F1-score of 92%. This reliable performance indicates that the model can effectively filter out unwanted spam messages with minimal disruption to legitimate communication.

Usage
Clone the repository: 
git clone https://github.com/sumanasreeshu/spam-detection.git

Download the necessary data files and open the Spam Detection.ipynb notebook.

Run the notebook to explore the **data preprocessing, feature engineering, model training, and evaluation steps.**

