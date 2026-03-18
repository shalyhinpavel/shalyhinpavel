# Pavel Shalyhin

### AI Solutions Architect | System Designer

I am an AI Solutions Architect and System Designer specializing in fault-tolerant cognitive architectures and neuro-symbolic memory systems. My approach is "Architecture First": I design logic, data flows, and failure points before writing code. 

Coming from an E-commerce portfolio management background, I build AI solutions with a clear ROI—either by radically reducing infrastructure costs or uncovering hidden profit (e.g., identifying €600k in hidden losses via custom ML pipelines).

---

## Signature Architectures & Research

### OneCeroOne (1C1) — High-Performance Local RAG Engine
A headless search engine built for privacy and efficiency.
* **Technology:** Rust (Axum, LanceDB, Tantivy) and Python (ONNX).
* **Optimization:** Used Rust to eliminate memory leaks common in Python-based RAG pipelines.
* **Performance:** Achieved 91.21% Recall@10 on the HotpotQA benchmark. Runs stable on entry-level hardware (Mac M1, 8GB RAM).
* **Link:** [onecero.one](https://www.onecero.one/)

### MYCELIUM — Neuro-Symbolic Memory for AI Agents
"Memory-as-a-Service" combining vector search with knowledge graphs.
* **Optimization:** Rewrote graph physics using LUA scripts inside Redis, reducing latency from 800ms to 40ms.
* **Architecture:** Implemented strict multi-tenancy and data isolation at the core level.
* **Link:** [myceliummemory.tech](https://www.myceliummemory.tech/)

### RIG-V3-GATEKEEPER — AI Security & LLM Firewall
Custom ML model designed to detect Prompt Injection and memory poisoning attacks.
* **Model:** Fine-tuned a Small Language Model (based on DeBERTa-v3) using custom Red Teaming datasets.
* **Metrics:** 99.32% Accuracy with a 0.00% False Positive Rate (FPR).
* **Deployment:** Optimized for CPU inference via ONNX format.
* **Link:** [Hugging Face Repository](https://huggingface.co/shalyhinpavel/RIG-V3-GATEKEEPER)

### ALICE — Meta-Cognitive Swarm Platform
An orchestrator for complex, multi-step reasoning using a Planner-Executor pattern.
* **Logic:** Dynamic agent spawning with deterministic behavior via strict typing (Pydantic) and Structured Outputs.
* **Safety:** Integrated secure sandbox for isolated Python code execution.

### GAUSS — Semantic Market Cartography
Unsupervised learning engine for high-dimensional market analysis.
* **Algorithms:** HDBSCAN, K-Means, and UMAP for clustering millions of products and reviews.
* **Impact:** Audited a €2M+ turnover account and identified €600,000 in hidden inventory losses by bypassing standard ERP reporting errors via custom BigQuery SQL.

---

## Technical Stack

* **AI & Machine Learning:** Python (3.12), Vertex AI, ONNX, PyTorch, DeBERTa/BERT, RAG, Multi-Agent Swarms.
* **High-Performance Backend:** Rust (Axum), FastAPI, AsyncIO, gRPC, WebSockets.
* **Data & Infrastructure:** Redis Stack (Graph), LanceDB, Tantivy, GCP (BigQuery, Cloud Run, Firestore), Docker.
* **Mathematics:** HDBSCAN, UMAP, K-Means, Vector Mathematics, Graph Theory.
* **Frontend:** React, TypeScript, Vite, Server-Driven UI (SDUI).

---

## Expertise & Roles

* **AI Infrastructure:** Development of local RAG engines and enterprise-grade agentic memory.
* **ML Engineering & Security:** Red Teaming, fine-tuning SLMs, and model optimization for CPU inference.
* **System Design:** End-to-end realization from database architecture to server-driven interfaces.

I am particularly interested in Technical Lead or Founding Engineer roles within AI-focused startups.

---

## Contact Information

* **Email:** contact@onecero.one
* **Telegram:** @paulshalyhin
* **LinkedIn:** [Pavel Shalyhin](https://linkedin.com/in/pavel-shalyhin)
