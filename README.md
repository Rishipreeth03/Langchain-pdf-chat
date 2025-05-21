# 📄 Langchain-pdf-chat

Langchain-pdf-chat is a simple and interactive Streamlit application that allows users to **chat with a PDF** using natural language. The app leverages **LangChain** and **OpenAI** to process PDF documents, understand user queries, and return accurate answers from the document’s content.

## 🚀 Features

- 📥 Upload any PDF and extract text from it
- ✂️ Split and chunk large documents efficiently
- 🔍 Use vector search (FAISS) to retrieve relevant information
- 💬 Ask questions and receive context-aware answers from OpenAI's language model
- ⚡ Built with LangChain, OpenAI, Streamlit, and FAISS

## 🛠 Tech Stack

- **Python**
- **LangChain**
- **OpenAI GPT (gpt-3.5-turbo / text-embedding-ada-002)**
- **FAISS**
- **Streamlit**
- **PyPDF2**

---

## 📦 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/langchain-pdf-chat.git
   cd langchain-pdf-chat

## **Set up your OpenAI API key:**

-- **Create a .env file in the root directory.**

-- **Add your OpenAI API key like this:**

    
    OPENAI_API_KEY=your_openai_api_key_here

--- 

##  **Run the App**

    streamlit run app.py

