🍳 AI Cooking Assistant

A simple AI-powered cooking assistant that lets you fetch recipes and ask questions about them interactively. Built using RAG (Retrieval-Augmented Generation) to provide context-aware answers.

🚀 Features
Fetch recipes dynamically using TheMealDB API
Convert recipe data into meaningful text
Semantic search using FAISS
Context-based Q&A using Groq LLM
Interactive chat in Jupyter/Colab
🛠️ Tech Stack
Python
LangChain
FAISS
Groq LLM
TheMealDB API
📂 Project Workflow
Fetch recipe from API
Convert to text format
Split into chunks
Store in FAISS vector DB
Retrieve relevant context
Generate answers using LLM
▶️ How to Run
pip install langchain langchain-community faiss-cpu groq requests

Run the notebook or script and enter a recipe name when prompted.

📌 Example
Enter recipe name: chicken curry  
You: what ingredients are needed?  
AI: ...  
📖 Learnings
Basics of RAG pipeline
Handling API data for LLMs
Working with embeddings and vector search
Managing conversational flow
