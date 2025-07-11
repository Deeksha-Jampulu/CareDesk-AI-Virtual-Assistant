# CareDesk AI – Virtual Assistant for Cerner EHR 🏥

**CareDesk AI** is a GenAI-powered, HIPAA-compliant virtual assistant built for CHC (Community Health Center) to help call center agents resolve Cerner-related queries.

## 💡 Problem

Agents faced delays handling technical Cerner issues due to lack of in-house EHR experts. CareDesk AI provides instant, contextual responses using a hybrid Retrieval-Augmented Generation (RAG) model.

## ⚙️ Tech Stack

- **Streamlit** for user interface (`app.py`)
- **Amazon Bedrock (Titan/Mistral)** for LLM-based question answering
- **OpenSearch** for semantic document retrieval
- **AWS Lambda + API Gateway** for secure backend routing
- **Knowledge Base**: `kb_articles/` folder containing SOPs, guides, FAQs
- **Logs**: `caredesk_log.csv` tracks user queries and responses

## 👩‍💻 My Contribution

As part of a 4-member GenAI team at Simarn Solutions, I contributed to:
- Architecting the RAG pipeline with Bedrock + OpenSearch
- Developing the Streamlit chatbot interface
- Ensuring HIPAA-compliant logic in the backend
- Testing and presenting to CHC, Chuck E. Cheese, and Academy Sports stakeholders

## 📦 Contents

| File                  | Description                            |
|-----------------------|----------------------------------------|
| `app.py`              | Main application code                  |
| `caredesk_log.csv`    | Chatbot interaction logs               |
| `kb_articles/`        | Knowledge base documents (PDFs/HTML)   |
| `requirements.txt`    | Python dependencies                    |
| `README.md`           | This project description               |

---

## 🧠 Outcome

CareDesk AI is projected to reduce L1 IT support tickets by over 60% and improve issue resolution time for Cerner-related queries.

