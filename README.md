# Twitter Sentiment Classification using IndoBERT

## Project Overview

This project builds a **Twitter sentiment classification model** using **IndoBERT**, a transformer-based language model designed for the Indonesian language.

The goal of this project is to classify tweets into sentiment categories by leveraging **Natural Language Processing (NLP)** and **deep learning techniques**.

Transformer-based models such as **BERT** have become the state-of-the-art approach for many NLP tasks including sentiment analysis, text classification, and information extraction.

---

# Problem Statement

Social media platforms such as Twitter contain large amounts of public opinion data.

Organizations and researchers often need to analyze this data to understand:

- Public sentiment toward topics or events
- Customer feedback
- Social trends and opinions

Manual analysis of tweets is inefficient, so **machine learning and NLP models** are used to automate sentiment classification.

---

# Dataset

The dataset consists of **Indonesian tweets** labeled with sentiment categories.

Typical dataset features include:

- Tweet text
- Sentiment label

The dataset was cleaned and preprocessed before training the model.

---

# Technologies Used

This project was developed using:

- Python
- PyTorch
- Hugging Face Transformers
- IndoBERT
- Scikit-learn
- Google Colab / Jupyter Notebook

---

# Project Workflow

## 1. Data Preprocessing

Text preprocessing steps included:

- Lowercasing
- Removing URLs and special characters
- Tokenization using IndoBERT tokenizer
- Converting text into model input format

---

## 2. Model Selection

This project uses **IndoBERT**, a pretrained transformer model optimized for Indonesian NLP tasks.

The model was fine-tuned for **sentiment classification**.

---

## 3. Model Training

The model was trained using a supervised learning approach with labeled tweet data.

Training process included:

- Tokenizing input text
- Feeding tokens into IndoBERT
- Fine-tuning the model for classification

---

## 4. Model Evaluation

Model performance was evaluated using several metrics:

- Accuracy
- F1-score

Example evaluation results:

Accuracy: **78.25%**  
F1 Score: **0.72**

These results show that the model can effectively classify sentiment in Indonesian tweets.

---

# Key Results

The IndoBERT-based model achieved:

- **Accuracy: 78.25%**
- **F1 Score: 0.72**

This demonstrates the effectiveness of **transformer-based NLP models** for sentiment classification tasks in the Indonesian language.

