#  Email Spam Classifier

A machine learning project designed to classify emails as spam or not spam, using various features derived from the content of the emails.

---

##  Project Objective

The goal of this project is to build an email classifier using machine learning that can automatically detect whether a given email is spam. We focus on simple, interpretable features like text length, word count, and sentence count to understand and distinguish spam patterns from regular messages.

---

##  Dataset Overview

Total Emails: 5,169

Columns:
- `target` → 1 = Spam, 0 = Not Spam  
- `text` → Raw email content  
- `num_characters` → Number of characters in the email  
- `num_words` → Number of words in the email  
- `num_sent` → Number of sentences in the email  

---

##  Exploratory Data Analysis (EDA)

We performed extensive EDA to gain insights into how spam and non-spam emails differ.

Key EDA Activities:
- Distribution plots of `num_characters`, `num_words`, and `num_sent`
- Box plots to compare features between spam and ham emails
- Correlation matrix and heatmap to identify linear relationships between numerical features
- Class balance check to verify if the dataset is imbalanced
- Outlier detection using histograms and scatter plots

Insights Gained:
- Spam emails tend to have higher character and word counts.
- Sentence counts are slightly higher in legitimate emails.
- All numerical features show weak-to-moderate positive correlation with the spam label.

---

## Technologies Used

- Python 3
- Jupyter Notebook
- Pandas – for data handling  
- Matplotlib and Seaborn – for visualization  
- (Modeling libraries can be added once implemented)

---

##  Workflow Summary

1. Load and clean the dataset  
2. Extract features from text (word count, character count, sentence count)  
3. Perform EDA and visualize key patterns  
4. Analyze correlations between features  
5. (Upcoming) Train machine learning models and evaluate performance  

---

##  Future Work

- Implement machine learning models (Naive Bayes, Logistic Regression, Random Forest)
- Add NLP-based features (TF-IDF, word embeddings)
- Perform hyperparameter tuning and cross-validation
- Deploy as a web app or integrate with email systems

---

##  Output

A well-prepared dataset with meaningful features and insights from EDA — ready to be used for training an effective email spam classifier.
