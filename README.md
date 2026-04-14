# 🤖 RAG Agent
A Retrieval-Augmented Generation (RAG) based AI Agent built using **n8n**, integrating **OpenAI**, **Supabase Vector Store**, and **PostgreSQL memory** to enable intelligent, context-aware conversations.
## 🚀 Features
- 🔍 Semantic search using vector embeddings  
- 🧠 Context-aware responses with chat memory  
- 🔗 Integration with OpenAI LLMs  
- 📂 Automated document ingestion pipeline  
- ⚡ Workflow orchestration using n8n  
## 🧩 Architecture
### 🔄 Workflow Overview
![RAG Workflow](assets/rag-workflow.png)
### 🧠 Pipeline Flow

User Query  
↓  
Embedding Generation (OpenAI)  
↓  
Vector Search (Supabase)  
↓  
Relevant Documents Retrieved  
↓  
LLM (Context + Query)  
↓  
Final Response

## 🛠️ Tech Stack
- **Workflow Automation:** n8n  
- **LLM & Embeddings:** OpenAI  
- **Vector Database:** Supabase  
- **Memory Storage:** PostgreSQL  
- **Data Processing:** Custom pipelines  
## 📌 Use Cases
- AI-powered document search  
- Knowledge base assistants  
- Chatbots with memory  
- Semantic search systems  
## ⚙️ Setup
1. Import the workflow:
## 🛠️ Tech Stack
- **Workflow Automation:** n8n  
- **LLM & Embeddings:** OpenAI  
- **Vector Database:** Supabase  
- **Memory Storage:** PostgreSQL  
- **Data Processing:** Custom pipelines  
## 📌 Use Cases
- AI-powered document search  
- Knowledge base assistants  
- Chatbots with memory  
- Semantic search systems  
## ⚙️ Setup
1. Import the workflow:

Rag Agent.json

2. Configure:
- OpenAI API Key  
- Supabase credentials  
- PostgreSQL connection  
3. Run the workflow in n8n  
## 📬 Future Improvements
- Add UI for user interaction  
- Improve retrieval accuracy  
- Support multiple data sources  
## 👨‍💻 Author
**Erico N Marak**





