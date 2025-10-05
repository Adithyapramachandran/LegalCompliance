# LegalCompliance

We propose an AI-powered Legal Compliance Assistant that automates contract management and compliance checking using LangChain. The system reduces manual effort and provides quick, reliable insights by combining document parsing, rule comparison, and intelligent generation.
       
Key Features:

Contract Review & Key Point Extraction

Checklist to identify the progress of all contracts under a specific movie

Users upload contracts in PDF/DOC format.

The system extracts important details (parties, dates, payment terms) and presents them in an easy-to-read format.

Compliance rules are applied, and missing/weak clauses are flagged as red warnings.

Contract Template Generation

Users enter contract details (e.g., parties, jurisdiction, duration) through prompts or forms.

The system automatically generates legally structured draft contracts (NDA, service agreement, etc.).

Drafts can be downloaded and further customized.

Search & Q&A over Uploaded Contracts

All contracts are stored in a vector database (ChromaDB) with embeddings for semantic search.

Users can ask natural questions like “What is the termination date of Contract X?” or “Which contracts involve Vendor Y?”.

The assistant retrieves relevant sections and provides clear answers.

Technologies Used:

LangChain → Orchestration framework for chaining LLM tasks.

GEMINI API → Large Language Models for contract analysis and generation.

ChromaDB → Vector database for storing contract embeddings and enabling semantic search.

Document Loaders (LangChain) → For PDF/DOC parsing.

Streamlit  → User interface for uploads, review, and search. 
