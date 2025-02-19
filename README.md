# **Retrieval-Augmented Generation (RAG) Application**

## **Overview**
This is a **simple RAG application** that allows users to **train their own PDFs** and then ask questions based on the content. The model provides responses **exclusively based on the information in the PDF**.

For development, we have two options:
1. **Using an online API**  
2. **Downloading a standalone LLM (Large Language Model) to run on a local machine**

## **How RAG Works**
RAG (Retrieval-Augmented Generation) enhances a language model by incorporating external knowledge retrieval. Here’s how it works:

1. **Document Ingestion:**  
   - The user uploads a PDF document.  
   - The system extracts relevant text data.  

2. **Indexing:**  
   - The extracted text is processed and stored in a vector database.  
   - Each chunk of text is converted into embeddings for efficient retrieval.  

3. **Query Processing:**  
   - When a user asks a question, the system converts the query into embeddings.  
   - The most relevant chunks from the indexed data are retrieved.  

4. **Response Generation:**  
   - The retrieved information is fed into the language model.  
   - The model generates a response based on the extracted content.  

## **Installation & Usage**
### **1. Clone the Repository**
```bash
git clone https://github.com/your-repo/rag-app.git

