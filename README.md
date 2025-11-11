# Build an Ask the Doc App

[![Run on Streamlit](https://img.shields.io/badge/Run%20on-Streamlit-FF4B4B?logo=streamlit&logoColor=white)](https://infs784-k6grfta8tbjxgff977evl4.streamlit.app/)



📘 Overview

This project demonstrates how to get answers from documents using embeddings, a vector store, and a question-answering (QA) chain. It builds on previous LangChain tutorials and shows how developers can use large language models (LLMs) to power intelligent applications such as chatbots, personal assistants, and automated content tools.

🚀 What You’ll Learn

In recent months, LLMs have gained significant attention for their ability to reason over text and provide context-aware answers.
This tutorial extends prior LangChain modules by integrating the following concepts:

Model I/O – Using an LLM and prompt templates to structure input and output.

Data Connection – Loading documents and splitting them into manageable text chunks.

Chains – Combining model logic into reusable pipelines (e.g., summarization or QA).

You will learn how to:

Create embeddings that represent text in numerical form.

Store those embeddings in a vector database for fast similarity searches.

Use a question-answering chain to retrieve relevant document sections and generate precise responses.

Build a working prototype called “Ask the Doc” that can answer questions about any text document.

🧩 Project Steps

The tutorial is divided into four main steps:

Document Loading – Import and preprocess text files using LangChain document loaders.

Text Splitting & Embeddings – Break documents into chunks and generate vector embeddings.

Vector Store Integration – Save and query embeddings for semantic search.

Question-Answering Chain – Use the retrieved chunks to provide accurate answers using an LLM.

🛠️ Technologies Used

LangChain – for model, data, and chain management

OpenAI or Hugging Face LLMs – for natural language understanding

FAISS / Chroma / Pinecone – for vector storage and retrieval

Python 3.10+
