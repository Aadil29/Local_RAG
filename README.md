# Local Retrieval-Augmented Generation (RAG) Application using LLaMA 2


## 🧠 Project Overview
This project implements a simple local Retrieval-Augmented Generation (RAG) system using LLaMA 2. The system can take a document (such as a PDF), convert it into embeddings, and answer natural language questions based on the content using a locally hosted LLM.

## ⚙️ What Was Built
A working prototype of a local RAG pipeline.

Embedded a document (in this case, a LinkedIn profile saved as a PDF).

Used a local LLaMA 2 model to answer questions about the content, such as:

"What are my top 3 skills?"

"What is my work experience?"

"What is my education background?"

The system provided accurate and relevant responses based solely on the document.

## 🔍 Current Limitations
The current version only handles in-memory document processing.

No persistent vector store is used yet,  which limits scalability.

There is no user interface; interaction is done directly through the notebook or code.

## 🚧 Next Steps & Improvements
Integrate a persistent vector store (e.g. Chroma, FAISS) to handle multiple documents and scale the knowledge base.

Build a basic user interface to allow easier interaction with the system.

Improve the retrieval and answer accuracy by refining chunking strategies, embeddings, and prompt design.

Add feedback loops to allow iterative tuning of model performance.
