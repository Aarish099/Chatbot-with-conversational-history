🤖 AI Chatbot with Conversation History and RAG
This is an advanced AI chatbot built using LangChain, designed to remember previous interactions and provide intelligent responses using both conversation history and document-based retrieval (RAG).

✨ Features
Session-Based Memory: Remembers past conversations using RunnableWithMessageHistory.

Multi-Session Support: Handle separate users or sessions with unique histories.

Dynamic Language Prompts: Responds in the language specified by the user.

Context Management: Trims old messages to stay within token limits using trim_messages.

Document Retrieval (RAG): Combines conversation with relevant information from documents using vector similarity.

Async Search Support: Enables faster and scalable document lookups.

🧱 Stack
Language Models: Gemma 2 (via Groq), LLaMA 3 (via Groq)

Embeddings: HuggingFace (MiniLM)

Vector Store: ChromaDB

Frameworks: LangChain, LangChain Community

📚 Data Sources
Custom documents about pets (dogs, cats, birds, etc.)

Embedded and indexed using sentence-transformers with Chroma for fast retrieval

📦 Dependencies
langchain, langchain_community, langchain_groq, langchain_huggingface

chromadb, faiss-cpu, sentence-transformers

dotenv, pypdf, bs4, arxiv, pymupdf, wikipedia

This project demonstrates how to combine conversation history and external knowledge sources using LangChain's modular tools. Ideal for developers exploring chatbots, memory management, and RAG workflows.
