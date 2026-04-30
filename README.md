# Keyword Test Automation (RAG Pipeline - AI/LLM)

**Overview:**
This project focused on automating test script generation using Large Language Models (LLMs) combined with a FAISS-based vector search system. The goal was to generate accurate, structured, and executable test scripts from step-based inputs while reducing errors such as hallucinated or missing methods.

**Problem Statement:**

**Initial LLM-based approaches led to:**
Hallucinated or incorrect test scripts
Missing or incomplete method mappings
Inconsistent code structure

**Solution Approach:**
Method Retrieval using FAISS
Converted method datasets into vector embeddings
Used FAISS for similarity-based method search
Retrieved relevant methods based on input test steps

**Test Script Generation:**
Combined retrieved methods with test steps
Used structured prompts to generate complete scripts
Ensured proper imports, class structure, and method calls

**Key Features:**
Automated test script generation from step inputs
FAISS-based method retrieval for improved accuracy
Reduced hallucination in generated outputs
Structured and executable test scripts

**Technology Stack:**
Python
FAISS
LLMs

**Results:**
Achieved ~95% accuracy in method retrieval
Reduced incorrect and hallucinated scripts
Improved consistency and reliability of generated test scripts
Faster execution and response time

**Learnings:**
Improved LLM outputs using retrieval-based approaches
Reduced hallucination through structured input design
Built scalable and efficient automation workflows
