# 🏥 Secure Healthcare LLM Chatbot using RAG and Role-Based Access Control (RBAC)

## 📌 Overview
This project is a secure AI-powered healthcare chatbot that answers medical queries while protecting sensitive patient information. It combines a Large Language Model (LLM) with Retrieval-Augmented Generation (RAG) to provide context-aware responses from hospital documents and patient records.

To ensure privacy, the system implements Role-Based Access Control (RBAC), allowing users to access only the information permitted for their role.

---

## 🎯 Problem Statement
Healthcare organizations increasingly use AI chatbots to assist patients and medical staff. However, these systems may unintentionally expose confidential patient information if proper access control is not implemented.

This project addresses that challenge by integrating RAG with RBAC to ensure secure and authorized access to medical information.

---

## 🎯 Objectives

- Build a secure healthcare chatbot using an LLM.
- Implement Retrieval-Augmented Generation (RAG).
- Store embeddings using FAISS.
- Generate synthetic patient records for testing.
- Restrict access using Role-Based Access Control (RBAC).
- Prevent unauthorized disclosure of sensitive healthcare information.
- Demonstrate secure AI deployment in healthcare.

---

## ✨ Features

- 🤖 LLM-powered chatbot
- 🔍 Retrieval-Augmented Generation (RAG)
- 🗂️ FAISS Vector Database
- 👤 Role-Based Access Control
- 🏥 Synthetic patient dataset
- 🔒 Secure document retrieval
- 📊 User authentication
- 📈 Scalable architecture

---

## 🛠️ Tech Stack

| Category | Technology |
|-----------|------------|
| Language | Python |
| LLM | Llama 3 / Mistral |
| Framework | LangChain |
| Embeddings | Sentence Transformers |
| Vector Database | FAISS |
| Frontend | Streamlit |
| Authentication | RBAC |
| Data | Synthetic Patient Records |
| Version Control | Git & GitHub |

---

## 🏗️ System Architecture

1. User Login
2. User Authentication
3. Role Verification
4. Query Processing
5. Embedding Generation
6. FAISS Retrieval
7. Context Injection
8. LLM Response Generation
9. Response Filtering
10. Final Response

---

## 🔄 Workflow

User Query
↓
Authentication
↓
Role Verification
↓
RAG Pipeline
↓
FAISS Retrieval
↓
LLM
↓
Secure Response

---

## 📂 Project Structure

```
Healthcare-LLM-Chatbot/
│
├── backend/
├── frontend/
├── data/
├── docs/
├── tests/
├── requirements.txt
├── README.md
└── LICENSE
```

---

---

## 🔒 Security Features

- User Authentication
- Role-Based Access Control (RBAC)
- Secure Retrieval
- Protected Patient Records
- Prompt Injection Resistance
- Least Privilege Access

---

## 📊 Results

- Successfully retrieves relevant medical documents.
- Prevents unauthorized users from accessing patient information.
- Generates accurate, context-aware responses.
- Reduces hallucinations through RAG.
- Demonstrates secure deployment of LLMs in healthcare.

---

## 🎨 UI/UX Design

### Figma Design

🔗 (https://www.figma.com/make/02T9s4Km02dRYkh4ywgV4c/Cybersecurity-Chatbot-Enhancements?fullscreen=1&t=IjNLM7ohYCDCHwJP-1)



## 📷 Screenshots

Add screenshots here.

Example:

- Login Page
- <img width="1348" height="543" alt="image" src="https://github.com/user-attachments/assets/ee5b5660-d9c9-4454-a721-740b257ff1b2" />

- Dashboard
- <img width="1346" height="541" alt="image" src="https://github.com/user-attachments/assets/e9367ee6-b41b-4b53-9460-bfc23eef3625" />

- Chat Interface
- <img width="1363" height="547" alt="image" src="https://github.com/user-attachments/assets/fedc5aa7-3bbe-4838-bc71-2ffb887116a2" />



## 🔮 Future Scope

- Multi-hospital support
- Audit logging
- Encryption of vector database
- Multi-factor authentication
- Voice-enabled chatbot
- Integration with Electronic Health Records (EHR)
- Deployment on cloud platforms

---

## 👩‍💻 Team Members

- Avishi Singla
- Shreya Sarin
- Sejal Bahri

---

## 📜 License

This project is developed for educational and research purposes.

---

## ⭐ Acknowledgements

- C-DAC Mohali
- Intel AI for Cybersecurity Program
- LangChain
- Hugging Face
- FAISS
- Figma
