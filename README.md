# 📝 Automatic Text Summarization System

## 📌 Overview
This project implements an **Automatic Text Summarization System** using **Natural Language Processing (NLP)** techniques. The system processes **news headlines** to extract key sentences and generate concise summaries using the **TextRank algorithm**.

### 🔹 **Key Features**
✅ **Text Summarization** – Extracts essential sentences for concise summaries.  
✅ **Multiple NLP Libraries** – Utilizes **spaCy, NLTK, and Scikit-learn**.  
✅ **TextRank Algorithm** – Graph-based ranking for sentence importance.  
✅ **Optimized Processing** – Efficiently handles large-scale text data.  

---

## 🏗 **Methodology**
### **1️⃣ Data Preprocessing**
- Tokenization & Stopword Removal.
- Lemmatization for better text representation.
- Sentence extraction for ranking.

### **2️⃣ Text Summarization Using TextRank**
- Constructs a similarity graph between sentences.
- Applies **PageRank-like scoring** to rank sentence importance.
- Extracts **top-ranked sentences** as the final summary.

### **3️⃣ Comparing NLP Libraries**
- Evaluated **NLTK, spaCy, and Scikit-learn** for text processing.
- **Conclusion**:  
  🔹 **spaCy is the preferred tool** for summarization due to its **robust ecosystem, efficiency, and advanced NLP capabilities**.

---

## 📊 **Results & Insights**
- ✅ **spaCy** excels in processing **complex text structures**.
- ✅ **Improved accuracy** over traditional **TF-IDF-based** approaches.
- 🔹 **Future Improvements**: Incorporate **transformer-based models (BERT, T5)** for enhanced performance.

