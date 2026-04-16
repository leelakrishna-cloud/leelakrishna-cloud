# Leela Krishna.T

> 💡 Building enterprise-grade Agentic AI systems for regulated environments, focused on reliability, traceability, validation, and governance.

Director | Data & AI Leader | Agentic AI & RAG | LLM Systems | Enterprise AI Transformation

---

## About Me

* Director-level technology leader with 20+ years of experience across Data, AI, and Banking  
* Deep expertise in regulatory data platforms, compliance, and data engineering  
* Currently focused on designing Agentic AI and RAG-based enterprise solutions  
* Specialized in building reliable, explainable, and traceable AI systems for regulatory and compliance-driven environments  
* Passionate about bridging AI innovation with real-world enterprise impact  

---

## Core Skills

* Generative AI (RAG, LLMs, Prompt Engineering)  
* Agentic AI & AI System Design  
* Machine Learning & NLP  
* Vector Databases (ChromaDB)  
* Data Engineering (ETL, Big Data, Data Platforms)  
* Python, SQL, Spark  
* Azure AI & Cloud Technologies  

---

## Featured Projects

### 1. Agentic AI Compliance Assistant (Latest)

An enterprise-grade AI assistant designed for compliance use cases using Retrieval-Augmented Generation (RAG), validation, and confidence scoring.

**Key Highlights:**
- Designed an end-to-end Agentic AI pipeline (Retrieval → Context Evaluation → Generation → Validation → Fallback → Confidence)  
- Implemented document-grounded response generation using ChromaDB  
- Built validation layer to reduce hallucination risk and ensure response accuracy  
- Enabled traceability through source attribution and chunk-level referencing  
- Added confidence scoring to indicate strength of supporting evidence  
- Implemented controlled fallback for out-of-scope queries  
- Developed an interactive Streamlit-based UI  

**Impact:**
- Improves reliability and traceability of AI-driven compliance workflows  
- Enhances decision support in regulatory and audit scenarios  
- Reduces risk of incorrect or non-compliant responses  
- Supports audit-ready and explainable AI outcomes  

**Tech Stack:** Python, Streamlit, LangChain, ChromaDB, OpenAI  

👉 GitHub: https://github.com/leelakrishna-cloud/agentic-ai-compliance-assistant

---

### 2. RAG-Based PDF Chatbot (GenAI)

A document-based chatbot for PDF question answering using RAG architecture.

**Key Highlights:**
- Built an end-to-end RAG pipeline  
- Implemented document ingestion, chunking, embeddings, and vector search  
- Used ChromaDB and LlamaCpp (BioMistral) for response generation  
- Developed a Gradio-based chatbot UI  

👉 GitHub: https://github.com/leelakrishna-cloud/rag-pdf-chatbot

---

## Key Differentiator

Unlike traditional chatbots, my solutions focus on:

- Document-grounded responses (RAG)  
- Traceability through source attribution  
- Validation of outputs  
- Confidence scoring  
- Controlled fallback mechanisms  

This enables reliable, explainable, traceable, and governance-driven AI systems for regulatory and compliance-intensive environments.

---

## Architecture (Agentic AI)

```mermaid
flowchart TD
    A[User Query] --> B[Retriever - ChromaDB]
    B --> C[Top K Relevant Chunks]
    C --> D{Relevant context found?}

    D -->|Yes| E[LLM - Generate from context]
    E --> F[Validation Layer]
    F --> G[Confidence Score]
    G --> H[Document-Based Response]

    D -->|No| I[LLM - General Knowledge]
    I --> J[Fallback Confidence]
    J --> K[General Knowledge Response]

## Explanation

RAG retrieves information, Agentic AI ensures reliability, traceability, validation, and governance.

---

## Certifications

Microsoft Certified: Azure AI Engineer Associate (AI-102)
Microsoft Certified: Azure Data Scientist Associate (DP-100)
Microsoft Certified: Azure AI Fundamentals (AI-900)
UBS Certified Data Scientist
UBS Certified Data Analyst
UBS Certified Engineer – Gold
UBS Certified Engineer – Silver
UBS Certified Engineer – Base
IBM – Exploratory Data Analysis for Machine Learning

---

## Currently focused on advancing:

Agentic AI architectures
Advanced LLM applications
Enterprise AI system design and governance

---

## Education

Currently pursuing a Ph.D. in Management (Business Analytics & AI/ML) at SRM University, India (expected 2029),
focused on applying AI and machine learning to real-world business and banking challenges.

---

## Connect

LinkedIn: https://www.linkedin.com/in/leelakrishnas/
Email: leelakrishnan@yahoo.com

