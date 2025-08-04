# RAG_Assg_Legal_Documents_NasrinKhatun
This assignment builds a Retrieval-Augmented Generation (RAG) pipeline for legal QA. It includes document chunking, embedding with FAISS, and answer generation via GROQ API. The system is evaluated using RAGAS metrics to assess answer quality and retrieval effectiveness.

### 🧾 Legal Document QA using RAG Pipeline
This project implements a Retrieval-Augmented Generation (RAG) pipeline for question answering over lengthy legal documents. Using semantic chunking, vector search, and large language models, the system retrieves relevant sections and generates grounded answers for user queries.

### 🔧 What’s Inside
Document Cleaning & Chunking: Raw legal texts are preprocessed, split into meaningful chunks, and embedded for retrieval.

Embeddings & Vector Store: Sentence-transformer embeddings are used with a FAISS vector index for fast similarity search.

RAG Pipeline: LangChain’s RetrievalQA chain is used with GROQ-hosted LLMs for answer generation.

Evaluation with RAGAS: The system is evaluated on question-answer pairs using RAGAS metrics like Faithfulness, Context Precision, Context Recall, and Answer Relevancy.

### 📊 Data Insight
Over 170K document chunks were created from long legal documents.

Documents varied in length and structure, with repeated legal terms and domain-specific clauses.

Chunk size and overlap were tuned to retain coherence and improve retrieval.

Recurring legal terms like agreement, party, and shall dominated the corpus.

### ✅ Highlights
The RAG system successfully retrieved and contextualized long, domain-heavy text.

Evaluation showed promising performance on accuracy and context relevance.

Preprocessing and chunking choices significantly influenced overall effectiveness.
