# 🕵️‍♂️ Fake Review Detection System (MK02)

## 📖 Overview
This project is a Machine Learning & NLP-based system designed to detect **fake and genuine reviews**. It uses both **traditional ML techniques** and **transformer-based deep learning models (DistilBERT)** to classify reviews accurately. The goal is to identify misleading reviews and improve trust in online platforms.

---

## 🚀 Features
- Detects fake vs genuine reviews  
- NLP preprocessing (cleaning, tokenization, stopword removal)  
- Machine Learning models implementation  
- Deep Learning using DistilBERT  
- Model comparison & pattern analysis  

---

## 🧠 Technologies Used
- Python  
- NLP (Natural Language Processing)  
- Scikit-learn  
- HuggingFace Transformers  
- DistilBERT  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

## 📂 Project Structure
Fake_Review_Detection_MK02/  
│  
├── Data/ → Dataset files  
├── src/ → Source code  
├── notebooks/ → Jupyter notebooks (training & analysis)  
│   ├── FRT(Distilbert).ipynb  
│   ├── Fake review.ipynb  
│   ├── pattern_analysis.ipynb  
├── requirements.txt → Dependencies  
├── README.md → Documentation  
└── .gitignore  

---

## ⚙️ Working Process
1. Data Collection → Reviews labeled as fake/genuine  
2. Preprocessing → Cleaning, tokenization, stopword removal  
3. Feature Extraction → TF-IDF & transformer tokenization  
4. Model Training → ML models + DistilBERT  
5. Evaluation → Accuracy, Precision, Recall, F1-score  

---

## 📊 Models Used
🔹 Traditional ML: Logistic Regression, Naive Bayes  
🔹 Deep Learning: DistilBERT (fine-tuned transformer model)  

---

## 📈 Results
- DistilBERT performs better than traditional ML models  
- Captures contextual meaning effectively  
- Higher accuracy in fake review detection  

---

## 🧪 Notebooks
- DistilBERT training notebook  
- Pattern analysis notebook  
- Model comparison notebook  

---

## 🛠️ Installation
```bash
git clone https://github.com/HARIOM8859/Fake_Review_Detection_MK02.git
cd Fake_Review_Detection_MK02
pip install -r requirements.txt
