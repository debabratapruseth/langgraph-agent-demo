# AI-Powered Workshop Planner and Meeting Assistant 

This is a LangGraph-based, AI-driven assistant prototype designed to help users plan workshops and meetings based on live weather data, document analysis, and AI-generated content — all within an interactive Colab notebook.

---

## Features

- **Conversational Interface** with limited memory (LangChain Memory)
- **Document-based Question Answering** using Retrieval Augmented Generation (RAG)
- **Live Weather API Integration**
- **Intent Classification and Task Routing** via LangGraph
- **Text-to-Image Generation** using OpenAI DALL·E-3
- **City Extraction from PDFs**
- **Workshop/Event Recommendations** based on weather
- **Multi-agent Controller** using LangGraph state machine

---

## System Workflow

1. Upload a PDF document (e.g., a city list)
2. Extract city names
3. Choose a city → get live weather info
4. Get indoor/outdoor activity recommendations
5. Provide agenda → generate a banner image
6. Ask questions from the uploaded PDF (RAG)

Each functionality is mapped to a node in the LangGraph state machine, orchestrated via user intent.

---

## Tech Stack

- `LangChain`, `LangGraph`
- `OpenAI GPT`, `DALL·E-3`
- `FAISS`, `PyMuPDF`, `OpenAIEmbeddings`
- `Weather API`
- `Google Colab`
  
---

##  Try it Now

Open Google Colab ( or any other platform you are using ); upload and run the attached code.
Use AI Assistant ( Gemini, CoPilot, ChatGPT etc.) for run time debugging and enhancing the code for your requirements.

---


##  Architecture Overview

The system follows a state-machine architecture enabled by LangGraph. Each node represents a modular task:
- Memory management
- PDF parsing and RAG
- Intent classification
- API calls
- Banner image generation

This design enables extensibility and clean orchestration of complex AI workflows.

---

##  Future Improvements

- Add a **Gradio/Streamlit UI** for non-technical users
- Handle more **edge cases and API failures**
- Upgrade to a **paid weather API** for forecasting capabilities
- Implement **alternate city suggestions** based on weather conditions

---


##  License

This project is open-source under the [MIT License](LICENSE).


---

# Blog Post

Blog URL : https://debabratapruseth.com/agentic-ai-for-beginners-learn-by-building-your-first-app/

Website : https://debabratapruseth.com/

---

👋 If you find this helpful, don't forget to ⭐ the repo and follow for more beginner-friendly AI projects!
