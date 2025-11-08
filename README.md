# 🧠 Personal RAG Chat Assistant – End-to-End Retrieval Augmented Generation Project

## 🚀 Project Overview
This project demonstrates an **end-to-end Retrieval Augmented Generation (RAG)** pipeline where I built a **personalized AI chatbot** capable of answering questions about **my own professional details** — instantly and accurately.

I used **LangChain**, **ChromaDB**, and **HuggingFace’s FLAN-T5** model to create a retrieval-based LLM system that reads my uploaded text file (containing my bio and project info), processes it into vector embeddings, and returns precise answers when queried.

---

## ⚙️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** LangChain, ChromaDB, HuggingFace Transformers, Gradio  
- **Embedding Model:** all-MiniLM-L6-v2  
- **LLM Used:** FLAN-T5-base  
- **Interface:** Gradio UI (for smooth browser-based chat)  

---

## 🧩 Workflow Breakdown
1. **Data Preparation:** Loaded a `.txt` file containing personal information.  
2. **Text Splitting:** Divided text into overlapping chunks using `CharacterTextSplitter`.  
3. **Embeddings:** Created semantic embeddings using `HuggingFaceEmbeddings`.  
4. **Vector Store:** Stored all chunks in **ChromaDB** for quick retrieval.  
5. **Retriever:** Configured similarity-based retrieval.  
6. **LLM Integration:** Loaded **FLAN-T5-base** model for natural language generation.  
7. **RAG Chain Construction:** Combined retriever + prompt + model via LangChain pipeline.  
8. **Interface:** Built an interactive **Gradio app** to query and visualize responses.

---

## 🧠 How It Works
1. Upload your `.txt` knowledge base (personal, company, or product info).  
2. Type any question in the Gradio interface.  
3. The model retrieves the most relevant chunks and formulates a natural answer.  

Example:
> **Question:** Who is Suryavhi Das?  
> **Answer:** Suryavhi Das is a Data Analyst skilled in machine learning, AI, and data visualization.  

---

## 🎯 Key Learnings
- Mastered **Retrieval-Augmented Generation (RAG)** architecture.  
- Understood **embedding creation** and **vector database management**.  
- Gained hands-on with **LangChain’s chaining concept**.  
- Built and deployed an interactive **AI-powered chatbot interface**.

---

## 🧩 Future Enhancements
- Integrate **Google Gemini API** for higher model performance.  
- Add **memory** for conversation context retention.  
- Build **multi-file document ingestion** for broader knowledge bases.

---

## 💻 Run It Yourself
1. Clone the repo  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   python app.py

## 🏆 Outcome

An intelligent chatbot that knows me personally and can answer any question about my career, education, or projects within seconds — all powered by RAG.

## 👤 Author

Suryavhi Das
Data Analyst | Gen AI Enthusiast | Machine Learning Practitioner
📧 Connect with me on LinkedIn : www.linkedin.com/in/suryavhi-das-a95094351
