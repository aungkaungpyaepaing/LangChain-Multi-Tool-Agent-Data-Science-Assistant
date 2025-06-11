# 🤖 LangChain Multi-Tool Agent: Data Science Assistant

This project demonstrates a custom **LangChain agent** designed to answer questions related to **data science course content**, while also using tools like **Wikipedia search**, **local vectorstore retrieval**, and Python introspection tools. Built with LangChain and OpenAI, the agent showcases modular tool calling and retrieval-augmented generation (RAG).

---

## 🚀 Key Features

- 🔍 **Wikipedia Search Tool**: Uses `WikipediaQueryRun` for live web search
- 📚 **Chroma Vectorstore Retriever**: Trained on an "Introduction to Data Science" course
- 🧠 **Memory & Prompt Templates**: Supports ongoing conversation and context tracking
- ⚙️ **Custom Tools**:
  - `get_python_version()` – Reports the Python version
  - `get_installed_packages()` – Lists installed Python packages

---

## 🧰 Tech Stack

- [LangChain](https://www.langchain.com/)
- [OpenAI API](https://platform.openai.com/)
- [Chroma DB](https://www.trychroma.com/) (Vector DB)
- Python tools: `platform`, `importlib.metadata`
- Jupyter Notebook (for interactive execution)

---


