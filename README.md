# 📘 SlideSense PDF Analyser

SlideSense is an **AI-powered PDF analyser** built with **Streamlit, LangChain, FAISS, HuggingFace embeddings, Sentence Transformers, and Google Gemini**.  
It provides an **ultra-smooth dark-themed UI** where you can upload any PDF, ask intelligent questions, and get contextual answers instantly.

---

## 🚀 Features
- 📂 Upload and process PDF documents
- ⚡ AI-powered question answering with **Google Gemini**
- 🔍 Semantic search powered by **FAISS** and **HuggingFace embeddings**
- 🎨 Sleek **dark blue & black gradient theme** with glassmorphism UI
- 🔒 Local document processing

---

## 🛠️ Tech Stack
- [Streamlit](https://streamlit.io/) – Frontend and web framework
- [LangChain](https://www.langchain.com/) – Document chain & LLM orchestration
- [FAISS](https://github.com/facebookresearch/faiss) – Vector similarity search
- [HuggingFace Embeddings](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) – Sentence-level embeddings
- [Google Gemini](https://ai.google/) – LLM for intelligent responses
- [PyPDF2](https://pypi.org/project/pypdf2/) – PDF text extraction

---

## ⚙️ Setup Instructions  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/Arsalan692/Slidesense-PDF-Analyser.git
cd Slidesense-PDF-Analyser
```

### 2️⃣ Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Set up API keys
   
   **🔑 Setting Up Google Gemini API Key**
   - Go to Google AI Studio: https://aistudio.google.com
   - Sign in with your Google Account.
   - Click Get API Key from the sidebar.
   - Create a new API key and copy it.

   **🔑 Get a HuggingFace API Token:**
   - Go to https://huggingface.co/settings/tokens
   - Create a token with read access
    
### 5️⃣ Add API Keys
**Create a .env file in the project root and add your keys:**
```bash
# GOOGLE API KEY
GOOGLE_API_KEY=your_api_key_here

# HuggingFace API Key
HUGGINGFACEHUB_API_TOKEN=your_huggingface_api_key_here
```

### 6️⃣ Run the app
```bash
streamlit run SlideSense.py
```
---

## 📽️ Watch Project Demo
**[▶️ Watch Demo Video (Google Drive)](https://drive.google.com/file/d/17Mq9Vs7x2XUoXm91TiYWcjbyFu4Jrp3V/view?usp=sharing)**
