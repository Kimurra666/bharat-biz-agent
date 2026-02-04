# 🇮🇳 Bharat Biz-Agent

Bharat Biz-Agent is a WhatsApp-first AI assistant designed for Indian small and medium business owners.  
The seller interacts only through WhatsApp (text or voice), while customers receive normal business messages such as invoices and payment reminders — without ever seeing AI.

---

## 🚀 What This Project Does

- Allows business owners to:
  - Create invoices via WhatsApp messages
  - Record udhaar (credit)
  - Send payment reminders
  - Detect UPI payments via screenshots
  - Prepare GST drafts (with approval)

- Uses **human-in-the-loop safety**:
  - No financial or legal action is executed without seller confirmation
  - Every sensitive action requires explicit approval

- Customers receive:
  - Normal WhatsApp invoices (PDF)
  - Polite payment reminders
  - No AI interaction exposure

---

## 🧠 Key Design Principles

- **WhatsApp-only UI** (no dashboards)
- **Voice & text supported**
- **Agent does the work, seller approves**
- **Customer never talks to AI**
- **Modular, Docker-first architecture**

---

## 🧱 Tech Stack

### Backend & AI
- Python 3.11
- FastAPI
- LlamaIndex (RAG)
- Chroma / FAISS (local vector store)
- Haystack (guardrails)

### Automation & Orchestration
- n8n (webhooks, reminders, automation)
- Flowise (LLM flow orchestration)

### Infrastructure
- Docker
- Docker Compose
