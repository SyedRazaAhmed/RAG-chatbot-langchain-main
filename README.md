# RAG-Based Knowledge Retrieval Prototype 🦜🔗🤗

A Retrieval-Augmented Generation (RAG) project built with LangChain and Hugging Face to retrieve information from custom documents and generate context-aware responses.

## Overview

This project demonstrates how Retrieval-Augmented Generation can be used to combine the power of pre-trained Large Language Models with domain-specific knowledge. The system first retrieves relevant content from a document collection and then uses that context to generate more accurate and useful answers.

The project reflects my interest in **GenAI, knowledge retrieval, and intelligent document processing**, which are also part of my broader background in **Data Science, AI, Python, SQL, and cloud-based ML workflows**. It is designed to show how AI systems can support evidence-based decision-making and practical knowledge access.

## Features

- Document ingestion and preprocessing.
- Semantic search using embeddings.
- Retrieval-based question answering.
- Response generation with Hugging Face models.
- Modular structure for easy experimentation and extension.

## Getting Started

### Environment Setup

Create and activate a virtual environment:

```bash
virtualenv venv
source venv/bin/activate
```

### Configure Environment Variables

Create a `.env` file and add your Hugging Face API token:

```bash
HF_TOKEN=your_huggingface_api_key
```

### Install Dependencies

Install the required libraries:

```bash
pip install -r requirements.txt
```

### Run the Application

Start the app using:

```bash
gradio app.py
```

This will launch the interface where you can ask questions and interact with the RAG chatbot.

## Usage

Once the application is running, enter a question in the chat interface and the system will retrieve relevant information before generating a response.

## Project Relevance

This project highlights skills in:

- Python development.
- Prompt engineering.
- Retrieval-Augmented Generation.
- Hugging Face and LangChain integration.
- Building practical AI tools for real-world information access.

## Additional Resources

- Hugging Face Spaces.
- Databricks Dolly 15k dataset.
- Dynamic-TinyBERT model.
- Sentence Transformers `all-MiniLM-L6-v2` model.
