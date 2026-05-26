# RAG Pipeline - n8n Workflow

## What it does
- Upload PDF via form → stores in Qdrant vector database
- Chat via Telegram → AI answers from your uploaded PDFs

## Requirements
- n8n (self-hosted)
- Qdrant (local or cloud)
- Ollama with llama3.2 model
- Telegram Bot

## Setup
1. Import the JSON into n8n
2. Set up Qdrant credential
3. Set up Ollama credential
4. Set up Telegram Bot credential
5. Create Qdrant collection named: rag_collection
6. Activate workflow

## Models Used
- llama3.2:latest (Ollama - free & local)
