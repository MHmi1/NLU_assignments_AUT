# 🚀 NLU Assignments - AUT

## 📖 Natural Language Understanding Course Assignments  

### 📌 Exercise 1: Persian Poem Meter Classification  
🔹 **Models Used:** XLM-RoBERTa, mT5, Bi-LSTM with Attention  
🔹 Tackled this problem as both a **sequence-to-sequence** task and a **token classification** task.  
🔹 Achieved **excellent accuracy** on the test dataset in both approaches.  

---

### 📌 Exercise 2: Intent Detection & Slot Filling  
**Dataset:** Amazon MASSIVE (Persian & English)  

#### 🏗️ Models Used:  
- **Encoder-only:** XLM-RoBERTa, BERT  
- **Decoder-only:** LLaMA 3.2-1B, GPT-3  
- **Encoder-decoder:** mT5  

⚠️ *Note:* Due to **infrastructure limitations** (**RTX 4060 Ti**), one training run didn’t complete fully, but I still demonstrated model performance and convergence.  

---

### 📌 Exercise 3: QA System with RAG  
🔹 **Task:** Designed a **Retrieval-Augmented Generation (RAG)** system for answering **complex Persian religious questions**.  

#### ⚡ Key Features:  
- **Clustering for Efficient Retrieval:** HDBSCAN, Agglomerative Clustering, K-Means 
- **Indexing:** FAISS vector database
- **Embeddings Model:** bert-base-fa-qa (fine-tuned for QA tasks)  
✅ Achieved **strong results** in both **k-related retrieval** and **LLM-based answer generation**.  

---

### 📌 Final Project: Multi-Turn Chatbot for Banking 🏦💬  
🔹 **LLM Used:** LLaMA 3.2-8B (quantized) + intent detection & slot-filling models  
🔹 **Purpose:** Built a **financial banking chatbot** that interacts with users and collects information in **JSON format** for API integration.  

---

### 🛠️ Technologies & Tools  
- **Libraries & Frameworks:** PyTorch, Tensorflow, Transformers, FAISS
- **Models:** XLM-RoBERTa, mT5, Bi-LSTM, LLaMA 3.2, GPT-3 ,Bert
- **Clustering Methods:** HDBSCAN, K-Means, Agglomerative  

---

### 📩 Contact & Contributions  
💡 If you're interested in contributing or discussing improvements, feel free to open an issue or reach out!  
