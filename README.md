# 📰 Fake News Detection System

## 📌 Overview
The **Fake News Detection System** classifies news articles as **Fake** or **Real** using **Machine Learning** and **Natural Language Processing (NLP)**.  
Our model leverages **TF-IDF vectorization** and **Logistic Regression** to capture textual patterns and achieve high accuracy in classification.

---

## 🎯 Objectives
- Detect whether a news article is fake or real.  
- Provide a scalable and lightweight system for real-time detection.  
- Achieve high accuracy using supervised ML techniques.  

---

## 📊 Dataset
- **Total articles:** 9,900  
  - Fake: 5,000  
  - Real: 4,900  
- **Attributes:**  
  - `Text` → News content  
  - `Label` → Classification (Fake/Real)  
- **Source:** Real & Fake News dataset (CSV format)  

---

## 🛠️ Project Architecture
1. **Data Input** → CSV file  
2. **Preprocessing** → Handle nulls, clean text  
3. **Split** → 80% training, 20% testing  
4. **Feature Extraction** → TF-IDF vectorization  
5. **Model Training** → Logistic Regression  
6. **Prediction** → Fake or Real  
7. **Evaluation** → Accuracy, Precision, Recall, F1 Score  

---

## 🤖 Algorithms Used
- **TF-IDF Vectorization** → Extracts text features  
- **Logistic Regression** → Classifies news as Fake/Real  

**Logistic Regression Equation:**  
\[
\hat{y} = \frac{1}{1 + e^{-z}}, \quad z = w^T x + b
\]

**Loss Function (Binary Cross-Entropy):**  
\[
L(y, \hat{y}) = -y \log(\hat{y}) - (1 - y)\log(1 - \hat{y})
\]

---

## 📈 Evaluation Metrics
- **Accuracy:** 99.24%  
- **Precision:** 99.27%  
- **Recall:** 99.17%  
- **F1 Score:** 99.22%  

---
