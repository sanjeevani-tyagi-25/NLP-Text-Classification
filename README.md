# 📰 NLP Text Classification using the 20 Newsgroups Dataset

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![spaCy](https://img.shields.io/badge/spaCy-NLP-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview

This project focuses on **Natural Language Processing (NLP)** by classifying news articles from the **20 Newsgroups Dataset** into one of 20 different categories.

The project demonstrates a complete NLP pipeline, including text preprocessing, feature extraction using **TF-IDF**, model training with **Multinomial Naive Bayes**, hyperparameter tuning using **GridSearchCV**, and performance evaluation using multiple classification metrics.

This project was completed as part of the **Data Science & Analytics Internship Program conducted by Vital Skills in collaboration with Tryst, IIT Delhi.**

---

## 🎯 Objectives

- Perform text preprocessing using NLP techniques.
- Convert text into numerical features using TF-IDF.
- Train a Multinomial Naive Bayes classifier.
- Optimize the model using GridSearchCV.
- Evaluate model performance using Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

---

## 📂 Dataset

**Dataset:** 20 Newsgroups Dataset

- Total Categories: **20**
- Text Documents: **18,000+**
- Dataset Source: Scikit-learn (`fetch_20newsgroups`)

Example Categories:

- alt.atheism
- comp.graphics
- sci.space
- rec.sport.baseball
- rec.sport.hockey
- talk.politics.misc
- talk.religion.misc

---

# 🔄 Project Workflow

![Workflow](images/workflow.png)

The workflow followed in this project is:

1. Load Dataset
2. Text Cleaning
3. Tokenization
4. Stopword Removal
5. Lemmatization
6. TF-IDF Vectorization
7. Train-Test Split
8. Model Training
9. Hyperparameter Tuning
10. Model Evaluation

---

# 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- spaCy
- NLTK
- WordCloud

---

# ⚙ NLP Preprocessing

The following preprocessing steps were applied:

- Lowercase conversion
- Tokenization
- Stopword Removal
- Lemmatization
- Text Cleaning

---

# 📊 Feature Extraction

The textual data was transformed into numerical vectors using:

- TF-IDF Vectorization

This converts text into machine-readable features while preserving the importance of words across documents.

---

# 🤖 Machine Learning Model

Model Used:

**Multinomial Naive Bayes**

Hyperparameter Optimization:

- GridSearchCV

---

# 📈 Results

## Class Distribution

![Class Distribution](images/class_distribution.png)

---

## Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

## Classification Report

![Classification Report](images/classification_report.png)

---

## Word Cloud

![Word Cloud](images/wordcloud.png)

---

# 📋 Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

# 📁 Project Structure

```
NLP-Text-Classification/
│
├── images/
│   ├── workflow.png
│   ├── class_distribution.png
│   ├── confusion_matrix.png
│   ├── classification_report.png
│   ├── wordcloud.png
│   └── tfidf_pipeline.png
│
├── NLP_Text_Classification.ipynb
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/NLP-Text-Classification.git
```

Go to the project folder:

```bash
cd NLP-Text-Classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
summer project.ipynb
```

---

# 📌 Key Features

- End-to-End NLP Pipeline
- Text Preprocessing using spaCy
- TF-IDF Feature Extraction
- Multinomial Naive Bayes Classifier
- Hyperparameter Tuning using GridSearchCV
- Performance Evaluation
- Data Visualization
- Confusion Matrix Analysis

---

# 🔮 Future Improvements

- Compare multiple machine learning algorithms.
- Implement deep learning models such as LSTM or BERT.
- Deploy the model as a web application using Flask or Streamlit.
- Improve preprocessing with advanced NLP techniques.

---

# 👩‍💻 Author

**Sanjeevani Tyagi**

B.Tech Computer Science & Engineering  
COER University, Roorkee

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!