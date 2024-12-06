# Multi-PDF Chatbot 🤖
Multi-PDF Chatbot is an advanced AI-powered document analysis tool using Google Gemini. It enables users to upload multiple PDFs, ask intelligent questions, and receive precise, context-aware responses through a user-friendly Streamlit interface. The application leverages semantic search and intelligent retrieval for comprehensive document interaction.

## 🚀 Key Features

The Multi-PDF Chatbot is an intelligent document interaction tool that allows users to:

- **Intelligent Document Processing:** Upload and analyze multiple PDFs simultaneously.
- **Contextual AI Interaction:** Ask precise questions and receive semantic search-driven responses.
- **Advanced Search Intelligence:** Leverage AI-powered deep document comprehension.
- **Persistent Knowledge Management:** Save, load, and track comprehensive chat histories.
- **Seamless Session Continuity:** Resume previous interactions with intelligent chat recovery.

## 📷 Chatbot Interface

**User Input & Customization**

![1](https://github.com/user-attachments/assets/5a49f6e8-33a7-4a20-bc08-8fad7cfa76b8)

**Generated Response**

![2](https://github.com/user-attachments/assets/ef7a90f8-3c40-43d2-a49c-b71ed764cbe9)


## 🛠 Technical Specifications

- **Frontend**: Streamlit
- **PDF Processing**: PyPDF2
- **AI Backend**: 
  - Google Generative AI (Gemini)
  - LangChain
- **Vector Database**: FAISS
- **Embeddings**: Google Generative AI Embeddings

## ⚙️ System Architecture

![WhatsApp Image 2024-11-14 at 23 17 55_431a4fbb](https://github.com/user-attachments/assets/6846d449-94a5-481d-b092-bda15aedaee6)


- Recursive text splitting for document processing
- Semantic similarity search
- Conversational question-answering chain
- Dynamic chat history management

## 📦 Getting Started

1. Clone the repository
```bash
git clone https://github.com/CodeWizardl/multi-pdf-chatbot.git
cd multi-pdf-chatbot
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Set up environment variables
- Create a `.env` file
- Add your Google API key: `GOOGLE_API_KEY=your_api_key_here`

4. Run the application
```bash
streamlit run app.py
```
5. **Access the Application:**
   Open your browser and navigate to `http://localhost:8501` to start interacting with the chatbot.

## ⚙️ Challenges and Solutions

### Document Processing
- **Challenge**: Handling large and diverse PDF documents
- **Solution**: 
  - Recursive text splitting
  - Semantic embedding for accurate context retrieval

### Chat History Management
- **Challenge**: Persistent storage of chat sessions
- **Solution**: 
  - JSON-based chat history storage
  - Dynamic filename generation
  - Timestamp-based organization

## 📚 Conclusion

The Multi-PDF Chatbot represents an innovative solution for intelligent document interaction, leveraging cutting-edge AI technologies to transform how users engage with PDF content.

## 📄 License

This project is licensed under the [MIT License](LICENSE).  
