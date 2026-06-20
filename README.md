# llm-agentic-RAG-2026

3 steps in the RAG pipeline

- Step 1: Retrieval
- Step 2: Build prompt
- Step 3: LLM

The are two helpers: 
 - rag_helper.py - the RAGBase class wrapping search, prompt building, and the LLM call
 - ingest.py - load_faq_data and build_index for loading the FAQ and building a minsearch index
