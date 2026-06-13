# RAG Chatbot — Recent Advances in AI (2025–2026)

A Retrieval-Augmented Generation (RAG) chatbot built with Groq that answers 
questions about the latest developments in Artificial Intelligence.

## What It Does
Ask questions about recent AI topics and get accurate, document-grounded answers:
- Agentic AI and Test-Time Compute
- Multi-Modal AI and Vision-Language-Action Models (VLAMs)
- Model optimization techniques (LoRA, QLoRA, Quantization)
- AI in scientific discovery and drug research
- AI safety, benchmark contamination, and emerging vulnerabilities

## Tech Stack
- **Groq** — LLM inference
- **LangChain** — RAG pipeline
- **FAISS** — vector similarity search
- **Google Colab** — development environment

## Setup
1. Get a free API key at [console.groq.com](https://console.groq.com)
2. Add it to Colab Secrets as `GROQ_API_KEY`
3. Upload `ai_advances.pdf` to the Colab session
4. Run all cells

## How It Works
The document is chunked, embedded into a FAISS vector store, 
and retrieved contextually to answer user queries using Groq's LLM.
