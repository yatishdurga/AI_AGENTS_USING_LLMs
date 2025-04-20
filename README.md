

#Agent 1. 🧠 Arithmetic AI Agent using LLaMA & Groq

This project demonstrates a simple yet powerful **ReAct-style AI agent** using the **LlamaIndex framework** and **Groq LLaMA-3.1** model. The agent is designed to handle basic arithmetic operations (addition, subtraction, multiplication, division) using tool-augmented reasoning via the LLM.

---

## 🚀 Features

- 🤖 **LLaMA-3.1-based LLM** powered by Groq for fast, low-latency inference  
- 🛠️ **Tool integration** using LlamaIndex's `FunctionTool` API  
- 🧮 Performs arithmetic operations via ReAct agent reasoning  
- 🔁 Interactive agent loop to solve queries like "What is 27 multiplied by 3, then subtract 4?"

---

## 🧱 Tech Stack

- `llama-index`
- `llama-index-llms-groq`
- Python 3.8+
- Jupyter Notebook

---

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/arithmetic-ai-agent-llama.git
   cd arithmetic-ai-agent-llama

######################################################################

# 🧠 Q&A Agent with RAG using LangChain, ChromaDB, and Groq LLM

This project implements a **Question Answering (Q&A) Agent** using **RAG (Retrieval-Augmented Generation)** with **LangChain**, **ChromaDB**, and **Groq's LLM (e.g., Mixtral)**. The agent loads a PDF document, splits it into manageable chunks, generates embeddings using a HuggingFace model, stores them in a vector store (Chroma), and finally answers user queries based on document retrieval and large language model reasoning.

## 📂 Project Structure

- Load unstructured documents (PDFs)
- Chunk documents using LangChain text splitters
- Generate dense vector embeddings
- Store embeddings in ChromaDB for fast retrieval
- Use Groq LLM (Mixtral) to answer natural language questions
- Returns both answers and relevant source documents

### 1. Install all dependencies

```bash
pip install chromadb==0.5.5 langchain-chroma==0.1.2 langchain==0.2.11 \
            langchain-community==0.2.10 langchain-text-splitters==0.2.2 \
            langchain-groq==0.1.6 transformers==4.43.2 \
            sentence-transformers==3.0.1 unstructured==0.15.0 \
            "unstructured[pdf]==0.15.0"
   
