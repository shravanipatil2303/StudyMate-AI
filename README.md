# 🎓 StudyMate AI

Your Personal Exam Preparation Assistant powered by RAG (Retrieval-Augmented Generation).

StudyMate AI helps students upload PDF notes and ask questions directly from their study material. The system retrieves relevant content from the uploaded PDF and generates accurate answers using Groq LLM.

---

## 🚀 Live Demo

🌐 https://studymate-ai-2026.streamlit.app

---

## ✨ Features

### 📄 PDF Upload
Upload your notes, lecture slides, or study material in PDF format.

### ❓ Question Answering
Ask questions directly from the uploaded PDF.

### 📝 Short Answer Mode
Generates concise exam-oriented answers in 4–5 sentences.

### 📚 Detailed Answer Mode
Generates structured, detailed answers suitable for exam preparation.

### ⚡ Fast AI Responses
Powered by Groq LLM for low-latency answer generation.

### 🔍 Semantic Search
Uses vector embeddings and FAISS to retrieve the most relevant content from documents.

---

## 🛠️ Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### AI & RAG
- LangChain
- FAISS Vector Database
- Sentence Transformers
- Groq LLM

### Document Processing
- PyPDF

---

## 📂 Project Structure

```bash
StudyMate-AI/
│
├── app.py
├── src/
│   ├── data_loader.py
│   ├── embedding.py
│   ├── vectorstore.py
│   └── search.py
│
├── data/
├── notebook/
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/shravanipatil2303/rag-pdf-question-answering.git
cd rag-pdf-question-answering
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux/Mac

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory:

```env
GROQ_API_KEY=your_groq_api_key
```

---

## ▶️ Run Application

```bash
streamlit run app.py
```

---

## 📸 Screenshots

### Home Page

(Add screenshot here)

### Question Answering

(Add screenshot here)

---

## 🎯 Current Features

- ✅ PDF Upload
- ✅ RAG-based Question Answering
- ✅ Short Answers
- ✅ Detailed Answers
- ✅ Streamlit Deployment
- ✅ Groq Integration

---


## 👩‍💻 Author

**Shravani Patil**

Computer Engineering Student

GitHub: https://github.com/shravanipatil2303

---

## ⭐ If you like this project

Give it a star on GitHub and share it with fellow students.
