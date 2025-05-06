# 💉 Injecto – A Medical Chatbot

Injecto is an AI-powered medical chatbot that provides reliable, context-aware responses to user medical queries using domain-specific knowledge. It combines modern AI tools like LangChain, FAISS, and Hugging Face LLMs with an intuitive Streamlit UI to deliver personalized, real-time assistance.

---

## 🚀 Project Overview

### 📌 Objective
Create an AI chatbot that:
- Answers user medical questions using verified literature
- Uses semantic search and LLMs for context-aware responses
- Delivers a smooth user interface experience

---

## 🧠 Knowledge Base

- **Primary Source**: *The Gale Encyclopedia of Medicine (2nd Edition)*
- Extracted, cleaned, and chunked medical content (~500 tokens)
- Converted into vector embeddings compatible with Mistral LLM

---

## ⚙️ Tech Stack

| Component | Tool |
|----------|------|
| Programming Language | Python 3.12.10 |
| Environment | venv |
| LLM | `mistralai/Mistral-7B-Instruct-v0.3` via Hugging Face |
| Framework | LangChain |
| Embedding Storage | FAISS |
| UI | Streamlit |
| IDE | VS Code |

---

## 🛠️ System Architecture

1. **Document Parsing**  
   Load and preprocess verified medical PDFs.

2. **Chunking & Embedding**  
   Split into semantic units (~500 tokens), generate embeddings.

3. **Vector Indexing**  
   Store embeddings using FAISS for efficient similarity search.

4. **LLM + RAG Pipeline**  
   Retrieve relevant chunks, generate answers via Mistral-7B using LangChain.

5. **Streamlit UI**  
   Interactive chatbot frontend for users.

---

## 🔐 API Key Handling

- Hugging Face Access Token stored in `.env`
- All `read` checkboxes selected while generating the token
- Specific repo access granted to `mistralai/Mistral-7B-Instruct-v0.3`

> ⚠️ **Important**: Keep your `.env` file secure and avoid committing it to version control.

---

## ✅ Features

- Accurate responses from trusted medical literature
- Retrieval-Augmented Generation (RAG)
- Lightweight and efficient with vector search
- Streamlit-based intuitive UI
- Tuned LLM parameters:
  - `temperature = 0.5`
  - `top_p = 0.95`

---

## 📸 Output Snapshot

*(Add your app screenshot here once available)*

---

## 🧪 Challenges Faced

- Handling PDF parsing inconsistencies
- Managing large vector stores and memory usage
- Maintaining high-quality, coherent answers

---

## 🔭 Future Scope

### 🧑‍💻 User Experience
- Secure login and user profiles

### 📁 Document Support
- Upload personalized medical PDFs for tailored advice

### 🌐 Interaction Expansion
- Multilingual support
- Voice-based interaction (speech-to-text and vice versa)

### 🧠 Knowledge Upgrades
- Real-time medical API integrations (e.g., CDC, WHO)
- Clinical trial datasets for deeper insights

---

## 📚 References

- [LangChain Docs](https://python.langchain.com/docs/introduction)
- [Hugging Face](https://huggingface.co)
- [Mistral LLM](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.3)
- [FAISS: Facebook AI Similarity Search](https://engineering.fb.com/2017/03/29/data-infrastructure/faiss-a-library-for-efficient-similarity-search/)
- [Streamlit Docs](https://docs.streamlit.io/)
- *The Gale Encyclopedia of Medicine (2nd Edition)*

---

## 🔗 GitHub Repository

👉 [Injecto - A Medical Chatbot](https://github.com/PranavAnand2005/Injecto---A-Medical-Chatbot.git)

---

## 📩 Contact

**Pranav Anand**  
📧 pranavofficialwork1234@gmail.com
---

**Thank you for visiting Injecto!** 🚑💬
