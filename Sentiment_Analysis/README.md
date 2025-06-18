# Sentiment Analysis using Hugging Face Transformers

This project performs sentiment analysis on airline tweets using Hugging Face's pre-trained transformer pipeline. The workflow includes data preprocessing, visualization, classification using the transformers library, and evaluation using various metrics.

## 🔍 Project Overview
• Task: Sentiment classification (positive/negative)

• Model: Pre-trained pipeline from Hugging Face (distilbert-base-uncased-finetuned-sst-2-english)

• Dataset: Airline Tweets dataset

• Libraries Used: transformers, pandas, numpy, matplotlib, seaborn, sklearn, torch

## 📁 File Structure

• sentiment_analysis_hugging_face.py: Main Python script (converted from Colab) containing all steps for sentiment analysis.

• Tweets.csv: Input dataset file (not included, needs to be placed in the working directory).

## 🚀 How to Run

1.Clone the repository.

2.Make sure you have all the required libraries installed:


command: pip install pandas numpy matplotlib seaborn scikit-learn transformers torch


3.Add the Tweets.csv file in the same directory.

4.Run the script:

command: python sentiment_analysis_hugging_face.py

## 📊 Features

• Pre-trained Model: Uses Hugging Face’s pipeline("sentiment-analysis")

• Binary Classification: Filters out neutral sentiments for binary classification

• Performance Metrics:

   • Accuracy

   • Confusion Matrix

   • ROC-AUC Score

## 📈 Sample Outputs

• Sentiment prediction for sample sentences

• Distribution plot of sentiment labels

• Confusion matrix heatmap

• ROC-AUC score display

## ✅ Results

• Achieved a reasonable accuracy and ROC-AUC score by applying a simple, pre-trained sentiment analysis pipeline directly on real-world tweets.

## 🛠️ Future Improvements

• Fine-tune the model on the airline dataset.

• Use more advanced preprocessing techniques (tokenization, cleaning).

• Expand classification to include neutral sentiment as a separate class.

## 📬 Contact

For questions or suggestions, feel free to reach out or open an issue.
