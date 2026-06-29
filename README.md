# Project 
Course- Applied AI
## Hi there 👋

A Spam Email Detection System built using Python, Scikit-learn, and Streamlit. The project uses Natural Language Processing (CountVectorizer) and a Machine Learning model to classify messages as Spam or Not Spam, with visualizations for model performance and a simple web interface for dataset preview.
A Machine Learning-based Spam Email Detection System using Python, Scikit-learn, and Streamlit. It classifies messages as Spam or Not Spam using NLP techniques and includes data visualization and a simple web interface.
📧 Spam Email Detection System using Machine Learning
📌 Project Overview
The Spam Email Detection System is a Machine Learning project developed to automatically classify email or SMS messages as Spam or Not Spam (Ham). The project applies Natural Language Processing (NLP) techniques to convert text into numerical features and trains a Machine Learning model to identify spam messages with high accuracy.

A lightweight Streamlit web application is also included to preview the dataset and demonstrate the project in an interactive way.

🎯 Objectives
Detect spam messages automatically.
Reduce unwanted emails and improve user security.
Learn text patterns using Machine Learning.
Demonstrate the complete Machine Learning workflow from data preprocessing to prediction.
📂 Dataset
Source: Kaggle Spam Dataset

Dataset File: spam.csv

Samples Used: 1000 messages

Target Classes:

Ham (0) – Legitimate messages
Spam (1) – Unwanted or fraudulent messages
The dataset is cleaned by selecting only the required columns (label and message) and renaming them for easier processing.

⚙️ Project Workflow
1. Data Cleaning
Load the dataset using Pandas.
Remove unnecessary columns.
Rename columns to label and message.
Select the first 1000 records for efficient model training.
2. Text Preprocessing
Convert email text into numerical vectors using CountVectorizer.
Create a vocabulary of unique words.
Transform messages into a sparse feature matrix suitable for Machine Learning.
3. Model Training
Split the dataset into 80% training and 20% testing.
Train a Linear Regression model.
Predict whether a message is Spam or Not Spam.
4. Model Evaluation
Calculate prediction accuracy.
Test the model with custom messages.
Visualize the prediction results using graphs.
✨ Features
📂 Dataset preprocessing and cleaning
📝 Text vectorization using CountVectorizer
🤖 Machine Learning-based spam detection
📊 Accuracy evaluation
📈 Scatter plot for Actual vs Predicted values
📉 Bar chart showing Spam vs Ham distribution
🌐 Streamlit web interface for dataset preview
💬 Custom message prediction
🛠️ Technologies Used
Python
Pandas
Scikit-learn
CountVectorizer (NLP)
Linear Regression
Matplotlib
Streamlit
📊 Results
The trained model achieved approximately 98% accuracy on the selected dataset, demonstrating that Machine Learning can effectively classify spam and legitimate messages based on textual features.

📈 Visualizations
The project includes:

Spam vs Ham Distribution
Actual vs Predicted Classification
Model Accuracy Output
These visualizations help understand the dataset distribution and evaluate the model's prediction performance.

🚀 Future Improvements
Replace Linear Regression with classification algorithms such as Naive Bayes, Logistic Regression, or Support Vector Machine (SVM) for improved performance.
Implement advanced NLP techniques like TF-IDF, stemming, and lemmatization.
Build a real-time email prediction interface.
Support multilingual spam detection.
Deploy the application online using Streamlit Cloud.
💡 Conclusion
This project demonstrates a complete Machine Learning pipeline for spam email detection, covering data preprocessing, text vectorization, model training, evaluation, visualization, and deployment with Streamlit. It provides a practical introduction to Natural Language Processing and binary text classification while showcasing how AI can automate email filtering and enhance digital security.

lipsitamajhee/lipsitamajhee is a ✨ special ✨ repository because its README.md (this file) appears on your GitHub profile.
