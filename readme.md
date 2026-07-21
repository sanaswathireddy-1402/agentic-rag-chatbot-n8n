# Agentic RAG Chatbot using n8n

## Overview

This project is an end-to-end Retrieval-Augmented Generation (RAG) chatbot built using n8n.

The chatbot retrieves information from uploaded PDF documents stored in Pinecone and generates answers using OpenAI.

## Features

- PDF Document Ingestion
- Google Drive Integration
- Text Chunking
- Google Gemini Embeddings
- Pinecone Vector Database
- OpenAI Chat Model
- n8n Workflow Automation
- Conversational Question Answering

## Tech Stack

- n8n Cloud
- OpenAI GPT
- Google Gemini Embeddings
- Pinecone
- Google Drive
- LangChain

## Workflow

Google Drive
→ Extract PDF
→ Text Splitter
→ Gemini Embeddings
→ Pinecone

User Question
→ OpenAI Agent
→ Pinecone Retrieval
→ Answer

## Screenshots

### Workflow

![Workflow](agentic_rag_chatbot_n8n\screen_shots\workflow_architecture.png)

### Chatbot

![Chatbot](agentic_rag_chatbot_n8n\screen_shots\Chat_bot_demo.png)

## Author

Suresh