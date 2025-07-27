# 🏥 Medicine Recommendation System using Symptoms

This project uses machine learning to recommend appropriate medicines based on symptoms provided by the user. It's designed to assist in early-stage diagnosis and help patients and healthcare professionals identify possible treatments without manual lookup.

<p align="center">
  <img src="medicine.jpg" alt="Medicine Recommendation System" width="500"/>
</p>

---

## 🚀 Features

* ✅ Predicts suitable medicine based on patient symptoms
* 🧠 Uses various ML classifiers 
* 📊 Detailed exploratory data analysis on symptoms and disease correlation
* 🗂️ Includes a user interface with a simple prediction pipeline 
* 📈 Evaluates models using accuracy, precision and confusion matrix

---

## 📂 Dataset

* Dataset contains **symptom-disease-medicine** mappings
* Over **100+ symptoms**, **40+ diseases**, and **50+ medicine names**
* Used label encoding and multi-feature classification

---

## 🔍 Exploratory Data Analysis

* Count plot of symptoms per disease
* Top frequent symptoms
* Heatmap for symptom correlation
* Word cloud of symptoms

---

## 💡 How It Works

1. User inputs symptoms (e.g., fatigue, headache, nausea)
2. Model predicts the most probable disease
3. Based on the disease, recommended medicine is displayed

---

## 🧪 Installation & Setup

```bash
git clone https://github.com/Gauri9977/Medicine_Recommendation_System_using_Symptoms.git
cd Medicine_Recommendation_System_using_Symptoms
jupyter notebook
```

---

## 📊 Results
The recommendation system successfully suggests alternative medicines based on similarity in drug descriptions and reasons for prescription using cosine similarity over TF-IDF vectorized text.

---

## ✅ Conclusion

This project demonstrates that content-based recommendation using NLP techniques like TF-IDF and cosine similarity can effectively suggest alternative medicines based on drug descriptions and use-cases. It offers a scalable solution for aiding healthcare professionals and pharmacists, with potential for future enhancements through integration of side effects, dosages, and advanced NLP models.

---
