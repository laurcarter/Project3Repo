# AI-Powered Healthcare Assistant: A RAG-Powered Healthcare Chatbot for Patients and Professionals

## Team Members:
 Lauren Carter,
 Domenic Guerrero,
 Sandeep Singh,
 Kevin Curry,
 Micah Purdome

## Overview
This Healthcare Assistant is powered by a Retrieval-Augmented Generation 
(RAG) pipeline. The application will assist users (patients and medical professionals) by: 
• Providing precise, evidence-based answers to medical queries. 
• Offering a voice-based interface using speech-to-text capabilities. 
The assistant will utilize LangChain for pipeline orchestration, Hugging Face and OpenAI models for NLP 
tasks, and recursive retrievers for efficient information retrieval. 

## Links to data
https://www.kaggle.com/datasets/pythonafroz/medquad-medical-question-answer-for-ai-research/data

## Core Frameworks
• LangChain: For pipeline orchestration. 
• Hugging Face: For transformer-based language models. 
• OpenAI GPT Models: For generative response generation. 
• Groq LLM (if available): High-performance NLP tasks. 


### 1. **Data Preprocessing**
   - Fetch and preprocess the MedQuAD dataset. 
   - Use semantic chunking to divide data into retrievable segments.
   - RAG Pipeline Development 
### 2. **Speech to Text Integration**
   
### 3. **Measure Performance**
   - RAGAS


## Analysis: 

The models that were used, like Random Forest, K Nearest Neighbors, Logistic Regression, and Gradient Boost, all got a high accuracy of 0.95. The Decision Tree was still good but a little lower, at 0.91.The utilization of grid search is optimal only in the case of the decision tree, where its implementation resulted in a 4% increase in performance.Our analysis concluded that the random forest was the most optimal model.
