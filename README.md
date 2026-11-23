### Hi, I'm Kamal — an AI engineer who has spent 13 years working with enterprise clients on their systems and their data.

I build RAG systems and LLM agents in Python, and I measure every change. My background is client delivery at Cognizant — currently on-site with a financial services client in Bristol — for financial services, healthcare, energy and retail clients: running requirements and design workshops, presenting findings to client stakeholders, estimating work for proposals, owning a retailer's incident management against its SLA, assessing a mainframe estate for migration to AWS, and putting AI tools to work on client code.
📍 Bristol, UK — open to London hybrid · AWS Certified Solutions Architect – Associate · AWS Certified AI Practitioner

---

#### 🔎 [Ask an engineering manual a question that needs a table, a diagram *and* a paragraph](https://github.com/pkamalprasath/ai-engineering-portfolio/tree/main/06.rag/projects/2.engineering-rag)
Multimodal RAG over text, tables and images. 50-question test set re-run after every change — best run **3.87/5**, multi-hop **2.63 → 3.27** (same judge). A regression was traced and reverted. 147 tests in CI.

#### ⚖️ [Three AI agents review a lending decision in parallel — and hand it to a human when unsure](https://github.com/pkamalprasath/ai-engineering-portfolio/tree/main/07.langgraph-compliance-agents/2.sentinel_v2)
11-node LangGraph workflow, BM25 → DistilBERT → local Llama 3.2 triage so only borderline cases reach a large model, human review below 0.85 confidence, SHA-256 provenance. Synthetic data. 200+ tests in CI.

#### 💬 [A Slack agent with 16 tools across Slack, GitHub and Notion — no agent framework](https://github.com/pkamalprasath/ai-engineering-portfolio/tree/main/04.slack-workflow-agent)
Hand-written agent loop on Claude's native tool use, FastMCP server, ChromaDB retrieval over channel history. 267 unit tests in CI.

#### 🧱 Built from scratch
LoRA in PyTorch with no PEFT library · an agent loop with no framework · GPT-2 124M pretraining on 8 GPUs (DDP), reimplemented following Karpathy's build-nanoGPT — [see the SLM notebooks](https://github.com/pkamalprasath/ai-engineering-portfolio/tree/main/08.slm-pretraining)

---

**At work:** designed and built a customer-service AI agent system on the OpenAI and Claude SDKs, with input and output guardrails, sized for about 10,000 interactions (pre-production); built two AI tools adopted by 40 colleagues and trained all 40; use Claude, Amazon Q and GitHub Copilot for business-logic extraction, code review and test generation on client code, with every output checked.

#### 🧰 Stack
| | |
|---|---|
| **Agentic frameworks** | OpenAI & Claude SDKs · LangGraph · LangChain · Claude tool use (framework-free agent loops) · MCP (FastMCP) · multi-agent orchestration · human-in-the-loop |
| **Context engineering** | RAG · hybrid retrieval (pgvector + BM25) · query decomposition · corrective RAG · parent–child chunking · agent memory |
| **Harness engineering** | LLM-as-judge evaluation harnesses · fixed test sets re-run per change · scenario harnesses for agents · guardrails (Guardrails AI, NeMo, Presidio) · Langfuse tracing |
| **Models** | Claude · OpenAI · Llama 3.2 via Ollama · PyTorch (LoRA, GPT-2 pretraining) |
| **Solution architecture** | AWS (Solutions Architect – Associate) · FastAPI services · Redis job queues · PostgreSQL · Docker Compose · GitHub Actions CI · Slack, GitHub & Notion API integrations |
| **Client delivery** | Requirements & design workshops · estimates for proposals · stakeholder demos & sign-off · incident management & SLAs · Scrum |
| **Enterprise & legacy** | COBOL · JCL · CICS · DB2 · Oracle · mainframe-to-AWS assessment · data masking (PHI/PII) |

[LinkedIn](https://www.linkedin.com/in/kamalprasath) · pkamalprasath@gmail.com
