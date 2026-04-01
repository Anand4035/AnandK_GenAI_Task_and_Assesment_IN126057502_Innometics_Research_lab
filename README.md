#Overview

This project performs sentiment analysis on movie reviews using Natural Language Processing (NLP) techniques and Machine Learning models. The goal is to classify reviews as positive or negative.

Tasks Covered
Task 1: NLP Preprocessing Pipeline
Task 2: Sentiment Analysis using Machine Learning
Dataset for task 2
The dataset used is the IMDB Dataset of Movie Reviews (for task 2,from the csv file,as the csv file is massive so i had reduced the data to 860 data)

Download Dataset: https://www.kaggle.com/code/nourhankarm/sentiment-analysis-of-movie-reviews-imdb-dataset/input

Note: Dataset is not uploaded due to size constraints. Please download it from the above link

#Project Pipeline

Raw Data → Preprocessing → Feature Engineering → Model Training → Evaluation → Comparison

NLP Preprocessing Steps
Lowercasing text
Removing punctuation
Removing stopwords
Tokenization
Lemmatization
Removing HTML tags and URLs
Feature Engineering
Bag of Words (BoW)
TF-IDF (Term Frequency - Inverse Document Frequency)
Models Implemented
Logistic Regression
Naive Bayes
Decision Tree
#Evaluation Metrics

Accuracy
Precision
Recall
F1 Score
#Results & Insights

Logistic Regression performed the best among all models
TF-IDF gave better results compared to Bag of Words
Achieved approximately ~90% accuracy
#Model Comparison

Model	Performance	Notes
Logistic Regression	Best	High accuracy and stable
Naive Bayes	Good	Fast but slightly lower accuracy
Decision Tree	Average	Tends to overfit
#Future Improvements

Word2Vec / Avg Word2Vec
Random Forest / XGBoost
Hyperparameter tuning
Deployment using Streamlit
#Technologies Used

#Python
#Pandas
#NumPy
#Scikit-learn
#NLTK

# Chatbot using Hugging Face Transformers

##  Objective
Build a conversational chatbot using a pre-trained transformer model.

##  Technologies Used
- Python
- Hugging Face Transformers
- PyTorch

##  Model Used
- DialoGPT-medium

##  Workflow
User Input → Model → Response Generation → Output

##  How to Run
1. Install dependencies
2. Run notebook
3. Start chatting

## 📷 Sample Output
 Chatbot: Hello! I am your AI assistant. Type 'exit' or 'quit' to stop.

 You: Hello
 Chatbot: Hi there! How can I help you today?

 You: What is Artificial Intelligence?
 Chatbot: Artificial Intelligence is the ability of machines to perform tasks that typically require human intelligence.

 You: Who created Python?
 Chatbot: Python was created by Guido van Rossum.

 You: exit
 Chatbot: Goodbye! Have a great day!
