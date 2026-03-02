# SMS-Spam-Classifier-Streamlit-NLP
# SMS Spam Classifier 📱 (NLP + Streamlit)

Classify SMS messages as **SPAM** or **HAM** using an NLP pipeline built with TF-IDF features and Logistic Regression, exposed via a Streamlit web app and a simple CLI.

## Overview

This project implements a complete text classification workflow for spam detection. It loads the SMS Spam dataset, transforms text into TF-IDF vectors, trains a Logistic Regression classifier, evaluates performance, and provides interactive ways to test the model.

## Features

- Automatic download or loading of SMS Spam dataset
- Text preprocessing and TF-IDF feature extraction
- Scikit-learn Pipeline with Logistic Regression
- Classification report with precision, recall, F1-score
- Streamlit web app for interactive message testing
- Command-line script to classify a single message

## Tech Stack

- Python
- Pandas
- Scikit-learn
- Joblib
- Streamlit
- Requests

## Project Structure

```text
sms-spam-classifier/
  ├─ data/
  │   └─ spam.csv
  ├─ src/
  │   ├─ train.py
  │   ├─ app_streamlit.py
  │   └─ predict_cli.py
  ├─ models/
  │   └─ sms_spam_pipeline.joblib
  ├─ requirements.txt
  └─ README.md
