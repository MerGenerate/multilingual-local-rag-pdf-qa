# Multilingual Local RAG System for PDF Question Answering

Live Demo: https://sozly2.birainydemo.com/rag

---

## Overview

This project is a local Retrieval-Augmented Generation (RAG) system that enables users to ask questions over PDF documents and receive context-aware answers.

The system currently supports Azerbaijani and is designed to scale to additional languages.

At its core, the solution uses a custom fine-tuned language model developed for this project, referred to as Sozly LLM.

---

## Problem

Organizations store critical knowledge in PDF documents, but:

- Manual search is time-consuming  
- Information retrieval is inefficient  
- Multilingual documents increase complexity  

---

## Solution

The system processes PDF documents, converts text into embeddings, and retrieves relevant content to generate accurate answers using a custom fine-tuned language model.

It is designed to run in a local or controlled environment, ensuring data privacy and full system control.

---

## Features

- PDF ingestion and text processing  
- Semantic search over document content  
- Question answering system  
- Azerbaijani language support  
- Custom fine-tuned language model (Sozly LLM)  
- Scalable architecture for multilingual support  
- Local deployment capability  

---

## Architecture

text
PDF Documents/n
   ↓
Text Extraction
   ↓
Chunking
   ↓
Embedding
   ↓
Vector Database
   ↓
Retrieval
   ↓
Sozly LLM
   ↓
Answer Generation
---

## Use Cases


Internal document search systems
Legal and policy document analysis
Knowledge base assistants
Multilingual document understanding
Private/offline document systems

---
## Tech Stack
Python
Retrieval-Augmented Generation (RAG) pipeline
Vector database
PDF parsing and text processing
Custom fine-tuned language model (Sozly LLM)
Local deployment environment

---
## Test the Product

Access the system here:
https://sozly2.birainydemo.com/rag

---

## Future Improvements

Expansion to additional languages
Improved retrieval accuracy
Enhanced user interface
Further model optimization
Available for collaboration and freelance opportunities.

---
## Team

A team of engineers building document understanding and automation systems.
