# PDF Chat Bot using Langchain Framework

## Overview
This project implements a chatbot that can interact with multiple PDF documents in a natural and coherent manner using a large language model (LLM) such as Gemini Pro. The chatbot is designed to understand and respond to various user queries, generate summaries, and provide insightful responses based on the content of the uploaded PDFs.

## Features
- **Natural Language Processing: Utilizes the Langchain framework and Gemini Pro API for understanding and generating human-like responses.**
- **PDF Interaction: Capable of processing and interacting with multiple uploaded PDF documents.**
- **Semantic Search: Employs a Vector Database for efficient and relevant information retrieval from the PDFs.**
- **Summary Generation: Automatically generates summaries of the PDFs and provides detailed responses to user queries.**

## Project Objectives
- **Develop a chatbot that can interact with multiple PDFs uploaded by users.**
- **Implement semantic search to enhance the chatbot's ability to retrieve relevant information.**
- **Ensure the chatbot can generate summaries and respond coherently to user queries.**

## Installation

1. **Clone the Repository**
   ```bash
   git clone <https://github.com/anamikalodhi01/AI-Chat-Bot.git>
   cd <repository-directory>

2. **Set Up a Virtual Environment**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
 
4. **Set Up Environment Variables**
    Create a .env file in the project root directory.
    Add your Gemini Pro API key to the .env file:
    GEMINI_API_KEY=your_api_key_here

## Usage
 
1. **Run the Streamlit App**
    ```bash
    streamlit run app.py

2. **Interact with the Chatbot**
   Open your web browser and go to http://localhost:8501.
   Upload one or more PDF files. Type your question in the input field and click "Submit" to get a response from the chatbot.

## Linkedin Post link 
https://www.linkedin.com/posts/anamika-lodhi-b3a9a2289_al-langchain-geminiapi-activity-7222491940473167872-UeB1?utm_source=share&utm_medium=member_desktop

## Screen Recording of the ChatBot
https://github.com/user-attachments/assets/41800961-bea2-4469-91c8-3bcd69fc2cbb




