# 🧠 Multi-Task Tweet Classification using ModernBERT

This project implements a multi-task learning framework using ModernBERT to classify tweets across multiple TweetEval tasks.

## Tasks Covered
- Emoji Classification
- Emotion Detection
- Sentiment Analysis
- Irony Detection
- Hate Speech Detection
- Offensive Language Detection
- Stance Detection

## Problem Formulation
Multi-task, single-label classification:
- One task per sample
- One label per task
- Missing labels masked with -100


## Training
- CrossEntropyLoss per task

## 📊 Validation
- Separate validation loop

## 🔮 Inference
Example:
predict("I love this 😄")

Output:
{'emoji': 7, 'sentiment': 1, ...}

## Installation
pip install torch transformers pandas tqdm

## ▶️ Usage
1. Load data
2. Train model
3. Validate
4. Predict


## 📄 License
MIT
