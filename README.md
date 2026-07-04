# Sentiment-Analysis-Project
Sentiment Analysis using Machine Learning and NLP
# Sentiment Analysis using Machine Learning

## 📌 Project Overview

This project performs **Sentiment Analysis** on text data using **Natural Language Processing (NLP)** and **Machine Learning**. The objective is to classify text into **Positive** or **Negative** sentiments and evaluate the performance of different machine learning models.

---

## 🎯 Objective

Build a machine learning model that classifies customer reviews into positive and negative sentiments using text preprocessing, TF-IDF feature extraction, and classification algorithms.

---

## 📂 Dataset

**Dataset:** Sentiment140 Dataset

Download from Kaggle:
https://www.kaggle.com/datasets/kazanova/sentiment140

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- WordCloud

---

## 📊 Project Workflow

1. Load the dataset
2. Explore the dataset (EDA)
3. Check missing values and duplicates
4. Text preprocessing
   - Convert text to lowercase
   - Remove punctuation
   - Remove stopwords
   - Tokenization
   - Lemmatization
5. Convert text into numerical features using TF-IDF
6. Split the data into training and testing sets
7. Train two machine learning models
   - Multinomial Naive Bayes
   - Logistic Regression
8. Evaluate the models using:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix
9. Generate WordClouds
10. Perform Error Analysis
11. Draw conclusions

---

## 📈 Visualizations

- Sentiment Distribution
- Review Length Distribution
- Confusion Matrix
- Positive WordCloud
- Negative WordCloud

---

## 🤖 Machine Learning Models

- Multinomial Naive Bayes
- Logistic Regression

---

## 📏 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

---

## 📌 Results

- Successfully classified customer reviews into positive and negative sentiments.
- Compared the performance of Naive Bayes and Logistic Regression.
- Logistic Regression provided better overall performance on the dataset.

---

## 💡 Real-World Applications

- Customer Feedback Analysis
- Product Review Classification
- Social Media Monitoring
- Brand Reputation Analysis
- Business Intelligence

---

## 📁 Project Structure

```
Sentiment-Analysis-Project/
│
├── Sentiment_Analysis.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## ▶️ How to Run

1. Clone this repository

```
git clone https://github.com/YourUsername/Sentiment-Analysis-Project.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Download the Sentiment140 dataset from Kaggle.

4. Place the dataset in the project folder.

5. Open the notebook and run all cells.

---

## 📦 Requirements

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- nltk
- wordcloud
