# Sentiment Analysis on Amazon Customer Reviews

This project performs **sentiment analysis** on Amazon customer reviews using Natural Language Processing (NLP) and machine learning techniques. It classifies the reviews into **positive** or **negative** sentiment based on review text and ratings.

## 🗂️ Dataset

- The data consists of **Amazon product reviews**.
- Reviews include both **textual feedback** and **ratings (1–5 stars)**.
- Ratings are used to label sentiment:
  - **1–2 stars** → Negative
  - **4–5 stars** → Positive
  - **3 stars** may be ignored or labeled as neutral (if used).

## 🧠 Models Used

The following ML classifiers were trained and compared:

- **Support Vector Machine (SVM)**
- **Logistic Regression**
- **Naive Bayes**
- **Decision Tree**

## ⚙️ Techniques & Tools

- Text preprocessing with **NLTK**
- **TF-IDF** vectorization
- Sentiment labeling from star ratings
- Training multiple models
- **F1 Score**, Accuracy, Precision, Recall for evaluation

## 📊 Evaluation Metrics

Each model is evaluated using:

- **F1 Score per class**
- Accuracy
- Precision
- Recall

## 📁 Files in This Repo

- `sentiment.ipynb` – Main Jupyter notebook with complete code
- `README.md` – Project overview

