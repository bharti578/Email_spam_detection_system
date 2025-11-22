Email Spam Detection

A machine learning project that identifies whether an incoming email is Spam or Not Spam (Ham).

⭐ Overview

Email spam has become a huge problem — from phishing scams to promotional junk.
This project uses machine learning to automatically classify emails as spam or not spam based on their content.

The goal is simple:
➡️ Help users filter unwanted emails automatically.

🧪 What This Project Does

Reads and cleans email text

Converts text into numerical features

Trains machine learning models

Predicts whether a new email is spam

Gives accuracy and performance reports

🧰 Technologies Used

Python

Pandas, NumPy

NLTK / Regex cleaning

Scikit-learn (ML models)

Jupyter Notebook

📂 Project Workflow
1️⃣ Load the Dataset

Reads the spam dataset containing text + labels (Spam / Ham).

2️⃣ Data Cleaning

Lowercasing

Removing punctuation

Removing stopwords

Lemmatization / stemming

3️⃣ Feature Extraction

Used TF-IDF Vectorizer to convert email text into machine-readable format.

4️⃣ Model Training

Trained algorithms like:

Logistic Regression

Naive Bayes

Random Forest
(whichever you used in the notebook)

5️⃣ Evaluation

Checked model performance using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix
