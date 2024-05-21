# OLLAMA-MISTRAL-RAG-Chain---Ask-RAG-Chain---Get-Web-Content-Answers

This repository contains the code for a RAG Chain Question Answering system that uses OLLAMA MISTRAL to extract insights from web articles.

Features
Load web documents from a specified URL.
Split documents into smaller chunks for better processing.
Generate embeddings for the text chunks using OLLAMA MISTRAL.
Store embeddings in a vector store for efficient retrieval.
Retrieve relevant documents based on a user's question.
Format retrieved documents and construct a prompt with the question and context.
Use OLLAMA MISTRAL's chat function to generate an answer based on the prompt.
Provide a user-friendly interface using Gradio for inputting URLs and questions.
Requirements
Python 3.7+
streamlit
bs4
langchain
langchain_community
OLLAMA
Installation
pip install -r requirements.txt
Usage
Clone the repository.
Install the required packages.
Run the following command:
streamlit run URLqa.py
Open http://localhost:8501 in your browser.
Enter a URL and a question in the provided fields.
Click the "Ask RAG Chain" button to get the answer.
Contributing
Contributions are welcome! Please see the CONTRIBUTING.md file for more information.

License
This project is licensed under the MIT License. See the LICENSE file for more information.
