# Mostafa Azami CV Chatbot

This repository contains the code for a **Streamlit-based chatbot** that provides interactive responses based on the contents of Mostafa Azami's CV. The chatbot utilizes **AWS Bedrock**, **LangChain**, **FAISS**, and **Streamlit** for an engaging and intelligent user experience.

[Mostafa Azami CV ChatBot](https://mostafaazami.streamlit.app/)


## 🚀 Features
- **Conversational AI**: Uses **Anthropic Claude-Instant-v1** via AWS Bedrock.
- **Document Retrieval**: Parses a **PDF CV** and performs **semantic search** using FAISS.
- **Streamlit UI**: Deploys a chatbot interface in a lightweight and easy-to-use web app.
- **Memory Retention**: Keeps chat history using **StreamlitChatMessageHistory**.




This will start a local Streamlit web app where you can interact with the chatbot.

## 🛠️ How It Works
1. **Loads CV Data**: The chatbot reads and indexes the PDF file (`Mostafa.Azami.CV2025.pdf`).
2. **User Asks a Question**: The chatbot receives a prompt via Streamlit UI.
3. **Semantic Search**: FAISS retrieves relevant CV content.
4. **LLM Processing**: The Claude-Instant-v1 model generates an answer.
5. **Response Displayed**: The chatbot provides a relevant answer based on the CV.

## 📜 Technologies Used
- **Streamlit** (for UI)
- **LangChain** (for AI-driven conversation)
- **AWS Bedrock** (Claude-Instant-v1 LLM)
- **FAISS** (Vector search for retrieving CV content)
- **Boto3** (for AWS integration)



---
**🚀 AI-powered CV Chatbot for seamless career interactions!**

