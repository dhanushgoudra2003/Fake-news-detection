# Fake News Detection 📰🔍

This repository contains a **Fake News Detection** system that leverages **Natural Language Processing (NLP)** and **Machine Learning** to classify news articles as **Real or Fake**. 

## 📌 Project Overview
- **Preprocessing:** Clean text data by removing noise (punctuation, numbers, stopwords, etc.).
- **Feature Extraction:** Use **TF-IDF Vectorization** to convert text into numerical format.
- **Model Training:** Train a **Logistic Regression** model for classification.
- **Prediction:** Classify new news articles as **Real** or **Fake**.

---

## 🚀 Features
✅ Text Cleaning and Preprocessing  
✅ TF-IDF Feature Extraction  
✅ Logistic Regression Model  
✅ Accuracy and Classification Report  
✅ Custom Function for New Article Predictions  

---

## 📂 Dataset
The dataset should contain:
- `text`: News content.
- `label`: **1** (Real) or **0** (Fake).  
You can use a dataset like the **Fake and Real News Dataset** from [Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset). 

## 📊 Results  
Our **Fake News Detection Model** achieved an **accuracy of 95%** on the test dataset.  

### 🏆 Performance Metrics:  
          precision    recall  f1-score   support  

       0       0.95      0.94      0.95      7089  
       1       0.94      0.95      0.95      7338  

accuracy                           0.95     14427  



✅ **Overall Accuracy: 95%**  

This indicates that the model performs **reliably well** in distinguishing between real and fake news articles.  
