# Custom Chatbot

## Overview
This project demonstrates the creation of a **Custom Chatbot** that can retrieve relevant information from an embedded dataset and generate responses using OpenAI's API. The chatbot leverages **retrieval-augmented generation (RAG)** by combining semantic search with contextual prompting to improve the quality of responses.

## Key Components

### 1. Data Wrangling
The project processes and structures a dataset into a usable format, ensuring it is suitable for embedding and retrieval.

### 2. Embedding Creation
OpenAI’s API is used to generate vector embeddings for the dataset, transforming text into numerical representations for efficient similarity search.

### 3. Vector Search
Cosine similarity is applied to search across the embedding space, allowing for the retrieval of the most relevant data points based on user queries.

### 4. Contextual Prompting
The retrieved search results are integrated into a prompt to provide context-aware completions, improving the chatbot’s ability to generate accurate and relevant responses.

### 5. LLM Completion
The final step involves making OpenAI completion calls using the contextually enriched prompt, enabling the chatbot to deliver coherent and informative responses.

## Objective
The primary goal of this project is to build a chatbot that intelligently retrieves relevant information and generates responses based on contextual awareness. This approach enhances chatbot interactions by making them more **accurate, informative, and context-driven**.