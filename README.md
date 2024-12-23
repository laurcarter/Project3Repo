# AI-Powered Healthcare Assistant: A RAG-Powered Healthcare Chatbot for Patients and Professionals

## Team Members:
 Lauren Carter,
 Domenic Guerrero,
 Sandeep Singh,
 Kevin Curry,
 Micah Purdome

## Overview:
This Healthcare Assistant is powered by a Retrieval-Augmented Generation 
(RAG) pipeline. The application will assist users (patients and medical professionals) by: 
• Providing precise, evidence-based answers to medical queries,
• Offering a voice-based interface using speech-to-text capabilities,
• The assistant will utilize LangChain for pipeline orchestration, 
• Hugging Face and OpenAI models for NLP,tasks, and recursive retrievers for efficient information retrieval. 

## Problem Statment:

Healthcare professionals and patients often struggle with information overload. This project seeks to
address:
• Difficulty in retrieving specific medical information quickly.
• The need for accurate, trustworthy answers to health-related questions.

## Objectives:

1. Build a healthcare assistant using RAG to retrieve and generate accurate responses.
2. Incorporate speech-to-text capabilities for improved accessibility.
3. Ensure responses are contextually relevant and supported by medical data.
   
## Links to data:
MedQuAD Dataset: A medical question-answering dataset with FAQs from Kaggle.

https://www.kaggle.com/datasets/pythonafroz/medquad-medical-question-answer-for-ai-research/data

## Core Frameworks:
• LangChain: For pipeline orchestration. 
• Hugging Face: For transformer-based language models. 
• OpenAI GPT Models: For generative response generation. 
• Groq LLM (if available): High-performance NLP tasks. 

## Key Features:
1. Natural Language Querying: Users can input text-based or voice-based queries.
2. Evidence-based Responses: Retrieve relevant information from the MedQuAD dataset and
other medical sources.
3. Voice Interaction: Integrate speech-to-text using Whisper for seamless voice input.

## Retrieval Tools:
• Recursive Retriever: For iterative retrieval of context-relevant chunks.
• Semantic Chunker: For chunking medical data based on semantic coherence.

## Database and Indexing:
• Chroma or FAISS: For vector storage and retrieval of embeddings.

## Workflow:
Step 1: Data Preparation
• Fetch and preprocess the MedQuAD dataset.
• Use semantic chunking to divide data into retrievable segments.
Step 2: RAG Pipeline Development
• Retriever: Implement recursive retrieval to fetch context-relevant chunks.
• Generator: Use OpenAI GPT or Groq LLM for generating responses based on retrieved data.
Step 3: Speech-to-Text Integration
• Incorporate Whisper for transcribing user queries from speech to text.
Step 4: Evaluation
• Measure performance using:
o RAGAS
   
## Results: 


