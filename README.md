# 🤖 RAG Chatbot – PDF Question Answering System

An AI-powered Retrieval-Augmented Generation (RAG) chatbot that allows users to upload PDF documents and ask questions based on their content.

## 🚀 Features
- Upload and process PDF documents
- Extract text from PDFs
- Semantic search for relevant information
- Generate AI-powered answers using Qwen2.5:3B
- Display relevant page references
- Maintain chat history
- Clear chat functionality

## 🛠️ Tech Stack
- Python
- Streamlit
- LangChain
- Sentence Transformers
- Scikit-learn
- Ollama
- Qwen2.5:3B

## 📂 Project Structure

```text
rag-chatbot/
├── app.py
├── requirements.txt
└── .gitignore
```

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/gunjansharma0019/Rag-chatbot.git
```

2. Open the project folder:

```bash
cd Rag-chatbot
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Install and start Ollama, then download the model:

```bash
ollama pull qwen2.5:3b
```

5. Run the application:

```bash
streamlit run app.py
```

## 🎯 Project Objective

To make information retrieval from PDF documents easier through AI-powered question answering using Retrieval-Augmented Generation.

## 👩‍💻 Author

Gunjan Sharma

GitHub: https://github.com/gunjansharma0019
