# 🕵️‍♂️ Fake Review Detection System (MK02)

## 📖 Overview
This project is a Machine Learning & NLP-based system designed to detect **fake and genuine reviews**. It follows a progressive modeling approach starting from **traditional ML (TF-IDF + Linear SVC)** to advanced **transformer-based models (DistilBERT and RoBERTa)** for improved accuracy and contextual understanding.

---

## 🚀 Features
- Detects fake vs genuine reviews  
- End-to-end NLP pipeline  
- Uses both traditional ML and deep learning models  
- Model comparison across different approaches  
- Pattern analysis of fake reviews  

---

## 🧠 Technologies Used
- Python  
- NLP (Natural Language Processing)  
- Scikit-learn  
- HuggingFace Transformers  
- DistilBERT, RoBERTa  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

## 📂 Project Structure
Fake_Review_Detection_MK02/  
│  
├── Data/ → Dataset files  
├── src/ → Source code  
├── notebooks/ → Jupyter notebooks (training & analysis)  
├── requirements.txt → Dependencies  
├── README.md → Documentation  
└── .gitignore  

---

## ⚙️ Working Pipeline

### 🔹 1. Data Preprocessing
- Lowercasing  
- Removing stopwords  
- Tokenization  
- Text cleaning  

---

### 🔹 2. Feature Extraction (Traditional ML)
- **TF-IDF Vectorization**
  - Converts text into numerical features  
  - Captures word importance  

---

### 🔹 3. Traditional Machine Learning Model
- **Linear SVC (Support Vector Classifier)**
  - Trained on TF-IDF features  
  - Efficient for high-dimensional text data  
  - Provides strong baseline performance  

---

### 🔹 4. Deep Learning Models

#### ✅ DistilBERT
- Lightweight transformer model  
- Faster and efficient version of BERT  
- Fine-tuned for fake review classification  

#### ✅ RoBERTa
- Optimized version of BERT  
- Better training strategy and performance  
- Captures deeper contextual relationships  

---

## 📊 Model Comparison

| Model                | Technique            | Performance |
|---------------------|---------------------|------------|
| TF-IDF + Linear SVC | Traditional ML      | Good baseline |
| DistilBERT          | Transformer (DL)    | High accuracy |
| RoBERTa             | Advanced Transformer| Best performance |

---

## 📈 Results
- Traditional ML (TF-IDF + SVC) provides a solid baseline  
- DistilBERT improves contextual understanding  
- RoBERTa achieves the best performance among all models  

---

## 🧪 Notebooks
- TF-IDF + Linear SVC implementation  
- DistilBERT training notebook  
- RoBERTa experimentation  
- Pattern analysis  

---

## 🛠️ Installation
```bash
git clone https://github.com/HARIOM8859/Fake_Review_Detection_MK02.git
cd Fake_Review_Detection_MK02
pip install -r requirements.txt
