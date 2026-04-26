📌 Authenticity Verification of Job & Internship Postings
🚀 Overview

This project presents an AI-powered system to detect fraudulent job and internship postings using Machine Learning (ML) and Natural Language Processing (NLP) techniques.

With the rise of online recruitment platforms, fake job postings have become a major issue. This system analyzes job descriptions and recruiter details to identify suspicious patterns and assign a reliability score, helping users avoid scams.

🎯 Features
🔍 Detects fake job and internship postings
🧠 Combines ML + Deep Learning models
📄 Text analysis using NLP techniques
📊 Reliability score generation
⚡ Real-time prediction
🌐 Web interface using Flask
🛠️ Tech Stack
Language: Python
Libraries: NLTK, spaCy, scikit-learn, TensorFlow / PyTorch
Models:
Logistic Regression
Random Forest
Support Vector Machine (SVM)
Bi-LSTM
BERT (Transformer)
Frontend/UI: Flask
Tools: NumPy, Pandas, Matplotlib
🧩 System Architecture
Input Job Posting → Preprocessing → Feature Extraction → ML/DL Models → Prediction → Reliability Score

🧠 Model Details
🔹 Data Processing
Text cleaning (remove stopwords, symbols)
Tokenization & Lemmatization
TF-IDF & Word Embeddings
🔹 Feature Engineering
Linguistic features (text patterns)
Metadata features:
Recruiter details
Salary anomalies
Posting frequency
🔹 Models Used
Classical ML: Logistic Regression, Random Forest, SVM
Deep Learning: Bi-LSTM
Transformer: BERT (best performance)
📊 Results
High accuracy in detecting fraudulent postings
BERT achieved best performance (~95%+ accuracy)
Improved detection using hybrid features (text + metadata)
