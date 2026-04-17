# 🚀 RAG-based Question Answering System using Amazon Bedrock

## 📌 Overview
This project implements a Retrieval-Augmented Generation (RAG) system using Amazon Bedrock.

It allows users to ask questions on enterprise documents stored in S3 and generates accurate answers based on retrieved data.

---

## 🧠 Architecture

User Query  
↓  
Amazon Bedrock Knowledge Base  
↓  
Retrieve relevant document chunks (Vector Search)  
↓  
Generate answer using Nova Micro model  

---

## ⚙️ Technologies Used

- Amazon Bedrock  
- Amazon S3  
- Titan Embeddings  
- Nova Micro Model  
- OpenSearch Vector Store  

---

## 📂 Dataset

- faq.txt  
- policy.txt  
- tech.txt  

---

## 🔄 Workflow

1. Upload documents to S3  
2. Create Knowledge Base in Bedrock  
3. Convert documents into embeddings  
4. Store in vector database  
5. Retrieve relevant chunks using semantic search  
6. Generate response using LLM  

---

## 🧪 Output

Example:

**Question:** How many leaves are allowed?  
**Answer:** Employees are entitled to 20 paid leaves annually.

✔ Accurate response  
✔ Based on uploaded documents  
✔ Includes citations  

---

## 📸 Screenshots
<img width="1920" height="895" alt="rag-kb-project" src="https://github.com/user-attachments/assets/e34b3534-555b-44a4-ac7c-4cea0f5c4df0" />
<img width="1918" height="886" alt="Test Knowledge Base rag-kb-project" src="https://github.com/user-attachments/assets/62e16517-86df-4aff-b5de-c366ac970289" />
<img width="1919" height="889" alt="Knowledge Bases" src="https://github.com/user-attachments/assets/8468542b-82d9-4f4e-8343-ea23888b84d4" />



---

## 🚀 Result

Successfully built a working RAG pipeline using Amazon Bedrock.

---

## 💡 Key Learning

This project demonstrates how RAG reduces hallucination by grounding LLM responses in real data.

---

## 👤 Author

Sohail
