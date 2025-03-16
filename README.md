# 🔥 Learning Transformer Architecture - Encoding & Decoding with 20 Newsgroups

## 📌 Project Overview
This repository is dedicated to **understanding and implementing the Transformer architecture** by working with **both Encoding and Decoding tasks** using the **20 Newsgroups dataset**.  

🚀 The goal of these projects is to explore how Transformers process text **from both perspectives**:
- **Encoding** - Understanding text representations (word embeddings & tokenization).
- **Decoding** - Generating text summaries using a trained Transformer model.

---

## 🧩 Project 1: Encoding 20 Newsgroups
📌 **Notebook:** [Encoding 20 Newsgroups](https://github.com/eyalshub/Trsformer/blob/main/encoding_20newsgroups.ipynb)

🔹 **What We Did:**
- **Preprocessed** the 20 Newsgroups dataset.
- **Explored tokenization techniques** (e.g., Word2Vec, BPE, SentencePiece).
- **Trained an encoding model** to generate embeddings.
- **Analyzed how different encoding methods impact text representation.**

📊 **Main Takeaways:**
- Understanding how words are converted into numerical representations.
- Experimenting with various encoding architectures.
- Preparing data for downstream tasks like classification or summarization.

---

## 🎯 Project 2: Decoding - Summarization with T5
📌 **Notebook:** `decoding_20newsgroups.ipynb` (To be uploaded)

🔹 **What We Did:**
- Built a **Transformer Decoder** from scratch.
- Faced major challenges (nonsense outputs, repetition, training instability).
- Switched to **Fine-Tuning T5** for a robust summarization model.
- Successfully **generated meaningful summaries** from 20 Newsgroups articles.

🔹 **Technologies Used:**
- PyTorch & Hugging Face `transformers`
- `T5-small` for summarization
- ROUGE score evaluation

📊 **Main Takeaways:**
- Understanding **how Decoders work** in NLP.
- Experimenting with **beam search & top-k sampling**.
- Fine-Tuning an **existing model** for better results.

---

## 🛠 Installation & Running the Code
### 🔹 **Clone the Repository**
```bash
git clone https://github.com/eyalshub/Trsformer.git
cd Trsformer

