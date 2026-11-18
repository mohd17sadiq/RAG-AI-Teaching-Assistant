# RAG-Based AI Teaching Assistant

An AI-powered teaching assistant that answers questions about course videos by retrieving relevant information from video transcripts and generating contextual responses using a Large Language Model.

## Features

- Video transcript processing
- Timestamp-aware text chunking
- Semantic search using vector embeddings
- Context retrieval using cosine similarity
- LLM-powered contextual question answering
- Relevant video timestamp identification

## Tech Stack

- Python
- Retrieval-Augmented Generation (RAG)
- Ollama
- Llama 3.2
- BGE-M3 Embeddings
- Pandas
- Scikit-learn

## How It Works

1. Extract and process video transcripts.
2. Split transcripts into meaningful chunks.
3. Generate embeddings for transcript chunks.
4. Retrieve relevant chunks based on user queries.
5. Provide retrieved context to the LLM.
6. Generate answers with relevant timestamps.

## Installation

```bash
git clone https://github.com/YOUR_USERNAME/RAG-AI-Teaching-Assistant.git
cd RAG-AI-Teaching-Assistant

pip install -r requirements.txt
```

Install and configure Ollama and the required model before running the application.

## Project Structure

Add your actual project directory structure here.

## Future Improvements

- Support multiple courses and video sources
- Improve retrieval accuracy
- Add evaluation metrics for answer quality
- Implement conversational memory
