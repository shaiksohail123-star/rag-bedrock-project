# 🚀 RAG-based Question Answering System using Amazon Bedrock

## 📌 Overview
This project demonstrates a Retrieval-Augmented Generation (RAG) system using Amazon Bedrock.
**This project reduces hallucination by grounding LLM responses in enterprise data using RAG.**

It allows users to ask questions on documents stored in S3 and receive accurate, context-based answers.

---

## 🧠 Architecture

User Query  
↓  
Amazon Bedrock Knowledge Base  
↓  
Retrieve relevant documents (Vector Search)  
↓  
Generate answer using Nova Micro Model  

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
2. Create Knowledge Base  
3. Convert text into embeddings  
4. Store in vector database  
5. Retrieve relevant data  
6. Generate response using LLM  

---

## 🧪 Output

Example:

**Question:** How many leaves are allowed?  
**Answer:** Employees are entitled to 20 paid leaves annually.

✔ Answer based on documents  
✔ Includes citations  

---

## 📸 Screenshots

## <img width="1920" height="895" alt="rag-kb-project" src="https://github.com/user-attachments/assets/2d1076e5-752b-4fac-8d8c-b3688e6bcc82" />
## <img width="1920" height="895" alt="rag-kb-project" src="https://github.com/user-attachments/assets/040038e7-ab27-4132-8c09-1d8186d69497" />
## <img width="1918" height="886" alt="Test Knowledge Base rag-kb-project" src="https://github.com/user-attachments/assets/afa40469-c68e-4f95-80f5-8a158726411e" />


---

## 🚀 Result

Successfully built a working RAG system using Amazon Bedrock.

---

## 👤 Author

Sohail
