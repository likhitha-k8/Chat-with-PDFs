# 📚 Chat with PDFs  

A Streamlit application that allows you to **chat with your PDF documents**.  
Upload one or more PDFs and ask questions in natural language. The app extracts text, splits it into chunks, creates embeddings, and lets you interact with your documents conversationally.  

---

## 🚀 Features  
- 📄 Upload multiple PDF files  
- ✂️ Automatic text extraction and splitting  
- 🔍 Embeddings with **OpenAI** (or HuggingFace fallback)  
- ⚡ Fast search with **FAISS**  
- 🤖 Ask questions and get accurate answers from your PDFs  

---

## 🛠️ Built With  
- [Python](https://www.python.org/)  
- [Streamlit](https://streamlit.io/)  
- [LangChain](https://www.langchain.com/)  
- [FAISS](https://faiss.ai/)  
- [OpenAI](https://platform.openai.com/) / [HuggingFace](https://huggingface.co/)  

---

## ▶️ How to Run  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/likhitha-k8/Chat-with-PDFs
   
2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
    # Windows
     venv\Scripts\activate
    # macOS/Linux
    source venv/bin/activate
   
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   
4. **Set your API key**
   Create a .env file in the root folder and add:
   OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxx

5. **Run the app**
   ```bash
   streamlit run app.py
   ```
   
6. Open in browser
   Go to http://localhost:8501
