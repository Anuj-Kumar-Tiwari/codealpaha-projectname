# CodeAlpha Data Analytics Internship - Task 3
# Sentiment Analysis on Customer Reviews

This folder contains the third task for the CodeAlpha Data Analytics Internship. The goal of this project is to perform Sentiment Analysis on a dataset of customer reviews using Natural Language Processing (NLP) techniques to classify customer feedback as Positive, Negative, or Neutral.

## 📌 Project Overview
This project analyzes text data to understand public opinion and customer satisfaction. It involves cleaning raw review text, calculating sentiment polarity, and comparing different NLP lexicons (TextBlob vs. VADER) to extract meaningful emotional trends from the data.

## 📊 Key Insights & Features
* Data Cleaning: Processed raw text by converting it to lowercase, removing special characters/numbers, and filtering out standard English stopwords using NLTK.
* Sentiment Classification (TextBlob): Calculated polarity scores to easily classify reviews into Positive, Negative, and Neutral categories.
* VADER Lexicon Analysis: Applied the NLTK SentimentIntensityAnalyzer (VADER) for a more robust, context-aware emotional detection.
* Model Comparison: Cross-analyzed and visualized the sentiment distributions between TextBlob and VADER.
* Rating Correlation: Correlated user-given star ratings (1-5) with the NLP-generated sentiment to validate the accuracy of the models.

## 📈 Visual Analysis
All generated visualizations are stored in the `charts` directory. Below are some of the key insights:

### Sentiment Distribution
![Sentiment Pie Chart](charts/sentiment_pie.png)
![Sentiment Bar Chart](charts/sentiment_bar.png)

### NLP Models Comparison
![Model Comparison](charts/comparison.png)

### Polarity & Ratings Correlation
![Rating Heatmap](charts/rating_heatmap.png)
![Polarity Distribution](charts/polarity_dist.png)

## 🛠️ Tech Stack & Libraries Used
* Language: Python
* Environment: Jupyter Notebook
* NLP Libraries: nltk, textblob, wordcloud
* Data & Viz Libraries: pandas, numpy, matplotlib, seaborn

## 🚀 How to Run Locally

1. Clone the repository:
   git clone https://github.com/AnujKumarTiwari/CodeAlpha_ProjectName.git
   cd CodeAlpha_ProjectName/Task_3

2. Install required dependencies:
   pip install pandas numpy matplotlib seaborn nltk textblob wordcloud notebook

3. Launch the Jupyter Notebook:
   jupyter notebook

---
💡 Developed by Anuj Kumar Tiwari as part of the CodeAlpha Data Analytics Internship.
