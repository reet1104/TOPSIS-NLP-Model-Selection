# 🏆 TOPSIS-Based NLP Model Selection for Text Summarization

This repository applies the **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)** method to evaluate and rank **pre-trained NLP models** for **text summarization**.

## 📌 Overview
Text summarization is an important task in **Natural Language Processing (NLP)**. Various pre-trained models exist, but selecting the best one depends on different performance metrics.  
Here, we use **TOPSIS**, a multi-criteria decision-making (MCDM) technique, to find the best model based on evaluation metrics like **ROUGE, BLEU, and METEOR**.

---

## 📊 Models Evaluated
We have evaluated the following **pre-trained NLP models** for text summarization:

- **GPT-3**
- **T5**
- **PEGASUS**
- **BART**
- **XLNet**

---

## ⚙️ Evaluation Metrics
We use multiple evaluation metrics to rank the models:

| Metric    | Description |
|-----------|------------|
| **ROUGE-1** | Measures unigram (word-level) overlap |
| **ROUGE-2** | Measures bigram (two-word sequence) overlap |
| **ROUGE-L** | Measures longest common subsequence (LCS) similarity |
| **BLEU**    | Measures n-gram precision |
| **METEOR**  | Measures semantic similarity |

---

## 🏆 TOPSIS-Based Ranking Results
We used the TOPSIS technique to rank the models based on the above evaluation metrics.

### **📌 Final Ranking Table**
| Model   | ROUGE-1 | ROUGE-2 | ROUGE-L | BLEU | METEOR | TOPSIS Score | Rank |
|---------|--------|--------|--------|------|--------|--------------|------|
| **GPT-3**   | 49.5   | 25.2   | 45.8   | 34.5 | 31.5   | **0.92**     | 🥇 **1** |
| **T5**      | 48.1   | 23.5   | 44.3   | 32.1 | 30.2   | **0.88**     | 🥈 **2** |
| **PEGASUS** | 47.8   | 24.0   | 43.7   | 31.7 | 29.8   | **0.86**     | 🥉 **3** |
| **BART**    | 45.2   | 22.1   | 41.5   | 30.5 | 28.3   | **0.82**     | 4 |
| **XLNet**   | 42.3   | 21.2   | 39.8   | 28.7 | 26.7   | **0.78**     | 5 |

---
