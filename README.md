# Admission_Guru

A chatbot built using IBM watsonx.ai to answer admission-related queries for MITAOE students using Retrieval-Augmented Generation (RAG).

## Features

- Uses Granite LLM via watsonx.ai
- Context-aware responses using embedded admission documents
- Frontend with Streamlit or Flask
- Python backend with watsonx.ai SDK
- Document search using built-in vector index

## Tech Stack

- IBM Cloud Lite (Free Tier)
- Granite LLM + RAG
- Python (Backend)
- Streamlit / Flask (Frontend)
- Data: `eligibility_criteria.txt`, `fees_structure.txt`, `documents.txt`

## Deployment Options

- IBM Cloud Functions  
- IBM Code Engine  
- IBM Cloud Foundry

## Testing & Updates

- Prompt Lab used for testing
- Model and embeddings updated via Watson Studio

## Optional Add-ons

- IBM AppID (authentication)
- IBM Cloud Object Storage (file storage)
