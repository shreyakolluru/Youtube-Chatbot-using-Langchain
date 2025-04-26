# Youtube-Chatbot-using-Langchain

## **YouTube Chatbot using LangChain + Cohere**

This project builds an AI-powered chatbot that can fetch, embed, and answer questions about any YouTube video using its transcript!

## 🚀 **Key Features:**

Fetches transcripts directly from YouTube videos 

Splits and stores content in a FAISS vector store for fast search 

Embeds text using Cohere embeddings 

Answers user questions or summarizes the video using Cohere Chat API 

Built with LangChain for easy modularity and scalability

## 🛠 **Tech Stack:**

LangChain

FAISS

Cohere API

YouTube Transcript API

Python 3

## 📦 **Installation**


git clone https://github.com/shreyakolluru/youtube-chatbot-langchain.git

cd youtube-chatbot-langchain

pip install -r requirements.txt

Or install manually:

pip install youtube-transcript-api langchain-community langchain-cohere faiss-cpu python-dotenv


## 🔑 **Setup**


Get your Cohere API Key from Cohere.

Create a .env file in the project root and add:

bash
Copy
Edit
COHERE_API_KEY=your-cohere-api-key

## 🎯 **How it Works**


Provide a YouTube video ID (example: Gfr50f6ZBvo).

Fetch the transcript automatically using YouTube Transcript API.

Split the transcript into chunks for efficient retrieval.

Embed those chunks using Cohere embeddings.

Store the embeddings in a FAISS vector database.

Use similarity search + LLM to answer questions based on the transcript.




