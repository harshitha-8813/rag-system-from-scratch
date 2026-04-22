# 🔍 RAG System From Scratch

> A fully working Retrieval-Augmented Generation (RAG) pipeline built 
> from scratch — no LangChain abstractions hiding the magic!

## 🧠 What is RAG?
Large Language Models (LLMs) don't know about YOUR private data.
RAG fixes this by:
1. Storing your data as searchable vectors
2. Finding relevant pieces when a question is asked
3. Feeding those pieces to the LLM as context

## 🛠️ Tech Stack
| Tool | Purpose |
|---|---|
| `LangChain` | Smart text chunking |
| `SentenceTransformers` | Convert text to vectors |
| `FAISS` | Lightning fast vector search |
| `Flan-T5` | Answer generation |

## 🚀 How to Run
1. Open the notebook in Google Colab
2. Run all cells in order
3. Ask any question about the knowledge base!

## 📁 Project Structure
- `rag_pipeline.ipynb` — Main notebook with full pipeline
- `my_knowledge.txt` — Sample knowledge base

## 💡 Example
Question: "What days can I work from home?"
Answer: "Mondays and Fridays"
