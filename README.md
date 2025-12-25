**Bengali Next-Word Prediction & Parts-of-Speech Tagging using Deep Learning
A comprehensive deep learning approach for predicting the next word towards sentence completion and determining parts of speech with morphosyntactic features of the Bengali Language.
🎯 Overview
This project implements two core Natural Language Processing (NLP) tasks for Bengali, a widely spoken language with over 250 million speakers:
1. Parts-of-Speech (POS) Tagging
Automatically assigns grammatical tags to each word in a sentence, identifying nouns, verbs, adjectives, and other parts of speech along with their morphosyntactic features.
2. Next-Word Prediction
Predicts the next word in a sequence to enable sentence completion and intelligent typing assistance, reducing typing effort particularly for users with special needs.

Key Highlights:

Custom Dataset: 77,433 hand-annotated Bengali tokens across 7,506 sentences
31 POS Tags: Comprehensive tagset following Microsoft Research India's IL-POST framework
Multiple Architectures: LSTM, BiLSTM, GRU, and Unidirectional Decoder Transformer
High Accuracy: BiLSTM achieves 98.39% accuracy on POS tagging
Large-scale Training: Models trained on up to 20M sequences for next-word prediction

Model Architectures
POS Tagging Models

LSTM: Unidirectional LSTM with 128 units

Parameters: 3.3M
Accuracy: 97.12%

🚀 Installation
Prerequisites

Python 3.7+
CUDA 11.0+ (for GPU support)
32GB RAM (minimum)
1TB disk space (for large datasets)

Step 1: Clone the Repository
git clone (https://github.com/JannatulFerdouseSornali/nwp-blstm-BN/tree/main)
cd bengali-nlp
Step 2: Create Virtual Environment
bashpython -m venv venv
source venv/bin/activate 
Step 3: Install Dependencies
bashpip install -r requirements.txt
Step 4: Download Pre-trained Models (Optional)
[bash# Download from releases or model zoo
wget ](https://github.com/JannatulFerdouseSornali/nwp-blstm-BN/blob/main/Final%20compiled-Sornali.xlsx)

💻 Usage
1. Running the Jupyter Notebook
bashjupyter notebook notebook/nwp-blstm-BN.ipynb

👥 Authors

Rakib Ahmed (191014033) - Email
Hasan Shahrier (182014027) - Email
Jannatul Ferdouse Sornali (181014043) - Email
