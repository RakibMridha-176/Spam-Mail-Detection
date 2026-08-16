# Spam-Mail-Detection
A machine learning-based spam email detection system using CountVectorizer and Multinomial Naive Bayes

# 📧 Spam Mail Detection using Machine Learning

A machine learning project for detecting whether an email is **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques and a Multinomial Naive Bayes classifier.

## 📌 Project Overview

Spam emails are unwanted messages that may contain advertisements, scams, phishing attempts, or other unsolicited content. This project builds a simple machine learning model to automatically classify emails as either:

- 🟢 Ham — legitimate email
- 🔴 Spam — unwanted or suspicious email

The project uses `CountVectorizer` to convert email text into numerical features and `MultinomialNB` to classify the messages.

## 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Scikit-learn
- CountVectorizer
- Multinomial Naive Bayes
- Jupyter Notebook
- Kaggle Dataset

## 📂 Dataset

The project uses a spam/ham email dataset containing email text and corresponding spam labels.

The dataset contains:

- `text` — email content
- `spam` — target label

Where:

- `0` = Ham / Not Spam
- `1` = Spam

## 🔄 Project Workflow

The project follows these steps:

1. Load the dataset
2. Explore the dataset
3. Check spam/ham distribution
4. Remove duplicate emails
5. Check missing values
6. Separate input features and target labels
7. Split the dataset into training and testing sets
8. Convert text into numerical features using CountVectorizer
9. Train a Multinomial Naive Bayes model
10. Evaluate model performance
11. Test the classifier with new email messages

## 🧠 Machine Learning Model

### CountVectorizer

`CountVectorizer` converts text documents into a matrix of token counts. This allows the machine learning algorithm to work with numerical representations of email text.

### Multinomial Naive Bayes

The project uses `MultinomialNB`, a Naive Bayes algorithm commonly used for text classification problems.

## 📊 Model Performance

The model achieved approximately:

**99.21% accuracy on the test dataset.**

> Accuracy may vary depending on the dataset version, preprocessing, and train-test split.

## 🧪 Example Predictions

The model was tested with sample emails such as:

```text
hey i am lokking for machine learning tutorial in begali language
