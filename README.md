# Resume QA System using OCR + Transformer

## Overview
This project is  a **Transformer-based semantic resume understanding system**.  
It uses:
- **OCR (EasyOCR)** to extract text from scanned PDF resumes
- **Sentence-BERT** to generate embeddings for semantic search
- **FAISS** for fast vector search
- **Rule-based post-processing** to improve accuracy for fact-based questions

## Features
- Upload PDF resume
- Ask questions like:
  - "What is the candidate's name?"
  - "What skills does the candidate have?"
  - "What experience does the candidate have?"
- Accurate semantic search + fact extraction

## Tech Stack
- Python 3.10+
- EasyOCR
- Sentence-Transformers
- FAISS
- PyMuPDF
- PIL / Pillow
- Google Colab compatible


