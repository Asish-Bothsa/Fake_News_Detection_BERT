# 📰 Fake News Detection using BERT

This project implements a fake news classification model using Hugging Face's pre-trained BERT model. The aim is to classify news articles as either **real** or **fake** based on their content, leveraging state-of-the-art transformer-based Natural Language Processing (NLP) techniques.

## 📌 Project Overview

I developed this project to deepen my understanding of transformer-based models for NLP classification tasks. It involves fine-tuning a pre-trained BERT model on a labeled news dataset for binary classification.

The workflow includes:
- Data preprocessing and cleaning
- Tokenization using Hugging Face's `BertTokenizer`
- Fine-tuning `bert-base-uncased` on the dataset using PyTorch
- Training the model and tracking loss and accuracy over epochs
- Evaluating model performance

## 📊 Dataset

The dataset consists of labeled news articles, identifying each as **real** or **fake**. It was processed and tokenized to prepare it for input into the BERT model.

## 🚀 Tech Stack

- Python  
- PyTorch  
- Hugging Face Transformers  
- Google Colab  
- Scikit-learn (for metrics and evaluation)

## 📌 Key Learnings

- Implemented data preprocessing and tokenization for transformer models  
- Fine-tuned a pre-trained BERT model for binary text classification  
- Gained hands-on experience with Hugging Face’s Transformers and PyTorch training workflows  
- Understood the importance of evaluation metrics in classification tasks

## 📦 How to Run
1. Clone this repository.
2. Open the Colab notebook.
3. Run all cells sequentially to reproduce the results.


*This project is part of my personal AI/NLP portfolio and reflects my hands-on exploration of transformer-based text classification tasks.*
