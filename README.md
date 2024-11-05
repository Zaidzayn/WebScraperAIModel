# WebScraperAIModel
This repository contains a Jupyter notebook that implements a Streamlit application for document-based question answering using LangChain, Hugging Face models, and FAISS for vector storage. The application enables users to query documents with answers that are retrieved and ranked based on relevance.


#Features
Document Loading: Loads documents from specified URLs and processes them using UnstructuredURLLoader.
Embedding Generation: Uses HuggingFaceEmbeddings to create embeddings for text data.
Vector Store: Implements FAISS for efficient vector storage and retrieval.
Question Answering: Employs LangChain’s RetrievalQAWithSourcesChain to answer questions based on loaded documents, providing sources for each answer.
