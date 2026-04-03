# CareGuide AI — RAG System for Home Care

A production-ready Retrieval-Augmented Generation (RAG) system built for the caregiving and home care industry. Features a full GUI interface, hybrid search, and 12 PDF knowledge base documents.

## Features
- Hybrid BM25 + Semantic search for accurate retrieval
- 12 PDF documents covering home care topics
- Conversation memory (last 8 turns)
- Confidence scoring (High / Medium / Low)
- Crisis detection with emergency alert
- Token and cost tracking
- Full GUI built with customtkinter

## Tools Used
- ChromaDB — vector database
- OpenAI API — embeddings and generation
- Sentence Transformers — semantic search
- customtkinter — GUI interface
- pypdf — PDF text extraction

## How to Run
1. pip install -r requirements.txt
2. Copy .env.example to .env and add your OpenAI API key
3. Add your PDF files to the documents/ folder
4. Run: python app.py

## Knowledge Base Topics
1. Types of home care
2. Costs and pricing
3. Medicare and Medicaid coverage
4. Dementia and Alzheimer's care
5. Hiring a caregiver
6. Caregiver qualifications
7. Post-surgery care
8. Home safety
9. Chronic conditions
10. Respite care and burnout
11. Questions to ask agencies
12. caregivers.com services
