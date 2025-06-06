🧠 Wikipedia Article Analysis & Classification

Final Project – "Big Data" Course
Master’s Program in Data Science

📌 Project Overview

This project is divided into two parts:

Part I: Exploratory Data Analysis (EDA) of Wikipedia articles
Part II: Machine Learning classification of articles into categories
The goal is to extract insights from a large dataset of Wikipedia articles and then build models capable of automatically assigning each article to the correct category.

📁 Dataset

The dataset includes Wikipedia articles grouped into the following 15 categories:

'culture', 'economics', 'energy', 'engineering', 'finance',
'humanities', 'medicine', 'pets', 'politics', 'research',
'science', 'sports', 'technology', 'trade', 'transport'
Each entry contains two main fields:

documents: full content of the article
summary: a short summary of the article
🔍 Part I – Exploratory Data Analysis (EDA)

The following metrics are calculated per category:

📄 Number of articles
✏️ Average word count per article
🧱 Maximum word count (longest article)
🪶 Minimum word count (shortest article)
☁️ Most representative word cloud
The goal of this step is to understand the structure, length, and lexical characteristics of the content in each thematic area.

🤖 Part II – Machine Learning Classification

In this part, we develop two classification models to predict the correct category of an article.

Models:
Model A – Trained using the documents column (full text)
Model B – Trained using the summary column (shorter text)
Objective:
Evaluate and compare the performance of both models in classifying articles.
Metrics used may include accuracy, F1-score, confusion matrix, etc.


🛠️ Tools & Libraries

Python (Pandas, NumPy)
Scikit-learn
NLTK / SpaCy (for NLP processing)
Matplotlib / Seaborn / WordCloud
Jupyter Notebooks (for analysis)
📈 Results & Insights

EDA reveals significant variation in article length across categories.
Word clouds highlight domain-specific vocabulary for each topic.
The model trained on documents generally performs better due to richer input, but summary-based models are faster and more lightweight.
