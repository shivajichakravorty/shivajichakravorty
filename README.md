# Hi, I'm Shivaji Chakravorty 👋

### AI Full Stack Engineer & Forward Deployed Engineer (FDE)

Computer Science Engineering graduate (**Sikkim Manipal**, 2018) with **8 years of enterprise customer operations & merchant advisory experience** at **PayPal** and **247.ai**, now building production-grade, privacy-first AI systems and full-stack web architectures.

Having spent years working directly with end-users, merchants, and cross-functional teams to diagnose operational bottlenecks, I bring a **Forward Deployed Engineering** mindset to software development—translating ambiguous real-world business and compliance pain points into resilient, end-to-end technical solutions.

📍 **Location:** Guwahati, India  
💼 **LinkedIn:** [linkedin.com/in/shivaji-chakravorty-585945372](https://www.linkedin.com/in/shivaji-chakravorty-585945372/)  
📫 **Email:** [shivaji.chakravorty5@gmail.com](mailto:shivaji.chakravorty5@gmail.com)

---

## 🚀 Featured Work & Current Focus

### 🛡️ [DocuShield AI](https://github.com/shivajichakravorty) *(Active Development)*
**Privacy-First Digital Document Signing & Legal Risk Audit Platform**

A distributed, multi-service platform designed to detect sensitive PII, audit contract clauses for legal risk, enable privacy-preserving document chat, and generate cryptographically verifiable signature trails.

- **Polyglot Microservices Architecture:** Built a decoupled system combining a **React + TypeScript + Vite + Tailwind CSS** client, a high-throughput **Node.js + Fastify** edge gateway with **BullMQ/Redis** async workers, and a **Python + Django** AI microservice—orchestrated via multi-container **Docker** setups.
- **Privacy-Preserving RAG & PII Masking:** Implemented hybrid vector retrieval (**PostgreSQL + `pgvector`**, local `BAAI/bge-small-en-v1.5` embeddings via `fastembed`) paired with **Microsoft Presidio**, **spaCy**, and `pdfplumber` for spatial PII bounding-box detection and reversible surrogate token masking before LLM inference (**Google Gemini 2.5 Flash**).
- **Cryptographic Auditability & Security:** Engineered tamper-evident **SHA-256** document hashing, automated PDF audit certificate generation, JWT authentication, and endpoint rate-limiting.
- **Automated Testing & Reliability:** Built end-to-end verification suites using **Playwright** (UI/auth flows), **Vitest** (Node gateway & cryptographic integrity), and **Pytest** (PII anonymization & contract audit pipelines).

---

## 📂 Additional Projects

### 🤖 Multi-Agent AI Customer Support System
- Engineered a full-stack **Django** support automation platform orchestrating **three autonomous AI agents** via **LangChain** and the **Claude API** to classify user intent, resolve support queries, and route escalations without human intervention.
- Built a **RAG pipeline** backed by **ChromaDB** for dynamic knowledge base context injection alongside a real-time observability dashboard streaming live agent execution metrics over **Server-Sent Events (SSE)**.

### 🛒 E-Commerce & Publishing Platform
- Developed a server-rendered commerce and content management application using **Python, Django, SQLite, HTML, and Bootstrap**, featuring product catalogs, user authentication, and integrated blogging workflows.

---

## 🛠️ Technical Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript (ES6+), Python, SQL |
| **Frontend & Streaming** | React, Vite, Tailwind CSS, Server-Sent Events (SSE), HTML5, CSS3 |
| **Backend & APIs** | Node.js, Fastify, Express, Django, Django REST Framework, REST APIs |
| **AI, Agents & RAG** | Google GenAI SDK (`gemini-2.5-flash`), Claude API, LangChain, Microsoft Presidio, spaCy, `fastembed`, `pgvector`, ChromaDB, `pdfplumber`, PyMuPDF |
| **Databases & Queues** | PostgreSQL, SQLite, Redis, BullMQ |
| **Testing & DevOps** | Docker, Playwright, Vitest, Pytest, Git, GitHub |

---

## 💡 What Drives My Engineering

- **Customer-First System Design:** 8 years at **PayPal** and **247.ai** taught me how software fails in the real world—and how to design intuitive, fault-tolerant workflows that reduce turnaround times and earn user trust.
- **Strict Type Safety & Modularity:** Enforcing clean separation of concerns across routes, services, custom hooks, and typed interfaces with zero tolerance for sloppy abstractions.
- **Building in Public:** Documenting architectural trade-offs, debugging lessons, and milestone progress openly on GitHub and LinkedIn.
