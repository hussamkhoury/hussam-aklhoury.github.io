# Hussam Kh

AI Engineer | LLM, RAG & Agentic Systems

---

## 👋 About Me

I am an AI Engineer with a strong backend and full-stack engineering background, focused on building **production-grade AI systems** rather than demos. My work centers on **LLM-powered applications**, **Retrieval-Augmented Generation (RAG)**, and **agent-based architectures**, with a strong emphasis on clean design, scalability, and real-world usability.

I have hands-on experience designing and deploying AI systems on **Google Cloud Platform**, working across the full lifecycle: from data ingestion and document intelligence, to model integration, backend APIs, and cloud deployment.

I enjoy solving complex problems where **AI meets system design**, and I care deeply about maintainability, observability, and long-term evolution of software systems.

---

## 🏛 Deloitte ME Tax Pulse – AI Tax Assistant

### **Overview**

Developed the core **AI‑Powered Tax Assistant** for **Deloitte Middle East**, designed to simplify highly complex tax regulations, ensure compliance, and support optimized tax strategies across the GCC (Gulf Cooperation Council) region. The system enables professionals to query and reason over large, continuously evolving repositories of tax laws, regulatory bulletins, and market updates.

### **My Role: Lead AI Engineer / Backend Developer**

Owned the end‑to‑end design and implementation of the AI assistant, with primary responsibility for **data ingestion pipelines**, **RAG architecture**, and a **hybrid agentic workflow** optimized for enterprise reliability and accuracy.

---

### 🚀 **Key Technical Contributions**

#### **1. Multi‑Modal Data Ingestion Pipeline**

* **Large‑Scale Ingestion:** Engineered a robust ingestion and vectorization pipeline capable of processing heterogeneous data sources, including **Word documents, PDFs, and complex Excel spreadsheets**.
* **Real‑Time Updates:** Integrated API‑based web scraping to continuously ingest tax alerts, regulatory changes, and market updates, ensuring the assistant remained current.

#### **2. Hybrid Workflow & Agentic Architecture**

* **System Design:** Implemented a **hybrid workflow / agentic architecture**. Core conversational flows follow deterministic paths for reliability, while **LLM‑based routing nodes** dynamically select tools or reasoning paths based on user intent.
* **Dynamic Context Switching:** Built a multi‑country context engine that tracks the active GCC jurisdiction (KSA, UAE, Qatar, etc.) and can **autonomously suggest context switches** when cross‑country tax questions are detected mid‑conversation.

#### **3. Advanced RAG Pipeline**

* **LLM Orchestration:** Leveraged **Google Gemini models** for advanced reasoning, synthesis, and response generation.
* **Vector Search:** Implemented semantic retrieval using **MongoDB Atlas Vector Search**, grounding responses in the most relevant tax clauses and significantly reducing hallucinations.
* **Tool Augmentation:** Integrated a **web search tool** to complement the internal knowledge base when handling breaking news or external economic events.

#### **4. Backend & Infrastructure**

* **Performance & Reliability:** Built the core service with **FastAPI**, delivering low‑latency, high‑throughput conversational interactions.
* **Cloud Deployment:** Deployed and managed the system on **Google Cloud Platform (GCP)**, aligning with enterprise‑grade security, scalability, and compliance requirements.

---

### 🛠️ **Tech Stack**

* **LLMs:** Google Gemini
* **Frameworks:** FastAPI, LangGraph (or custom workflow logic), Pydantic
* **Database:** MongoDB (Atlas Vector Search)
* **Cloud:** Google Cloud Platform (GCP)
* **Data Processing:** Python (Pandas for Excel, PyMuPDF for PDF parsing)

---

### 📸 **System Showcase & User Journey**

#### **1. Discovery & Entry**

The AI assistant is embedded within the broader **Deloitte ME Tax Pulse** ecosystem. Users first land on a centralized dashboard featuring real-time tax alerts and regional news. From there, they enter the AI Assistant, where an explicit **GCC jurisdiction selection** is required to ensure regulatory precision and legally grounded responses.

<p align="center">
<img src="dashboard.jpg" width="45%" alt="Deloitte Tax Pulse Dashboard" />
<img src="ai-entry.jpg" width="45%" alt="AI Assistant Entry" />
</p>
<p align="center"><em>Main dashboard with localized tax alerts (left) and the AI Assistant’s jurisdiction-aware entry point (right).</em></p>

---

#### **2. Contextual Querying & Grounded Retrieval**

Once a jurisdiction is selected (e.g., KSA), the assistant initializes with **region-specific legal grounding**. Users can issue high-level queries such as “VAT rates,” which are resolved through the RAG pipeline and returned as **structured, citation-backed responses**.

<p align="center">
<img src="vat-query.jpg" width="45%" alt="VAT Query Result" />
<img src="tax-applicability.jpg" width="45%" alt="Corporate Tax Applicability Logic" />
</p>
<p align="center"><em>Structured VAT rate breakdowns (left) and RAG-based reasoning for corporate tax applicability to non-residents (right).</em></p>

---

#### **3. Advanced Legal & Financial Reasoning (Zakat vs. Corporate Tax)**

A core complexity of the GCC tax landscape is the distinction between **Vat** and **Corporate Income Tax (CT)**. These examples demonstrate the LLM’s ability to perform **multi-factor legal reasoning**, explaining how tax obligations change based on **ownership structure, entity type, and religious versus statutory tax frameworks**.

<p align="center">
<img src="tax-comparison-1.jpg" width="45%" alt="Tax Comparison" />
<img src="tax-comparison-2.jpg" width="45%" alt="Ownership Structure Logic" />
</p>
<p align="center"><em>High-level comparative reasoning highlighting differences in nature of levy and ownership-based tax treatment between Vat and Corporate Income Tax.</em></p>

---

## 💰 LUNA – AI Financial Coach (MALY)

### **Overview**

LUNA is a hyper‑personalized **AI financial coach** integrated into **MALY**, a financial wellness platform. Unlike traditional chatbots, LUNA operates as a behavioral coach, combining real‑time financial data with behavioral finance principles to guide users toward healthier spending and saving habits.

### **My Role: AI Product Engineer & Systems Architect**

Led the development of LUNA’s intelligence layer, focusing on the intersection of **Open Banking data**, **behavioral finance**, and **AI‑driven recommendations**, while also building the administrative infrastructure required to manage the AI’s knowledge base at scale.

---

### 🚀 **Key Technical Contributions**

#### **1. Data‑Driven Behavioral Coaching**

* **Contextual Intelligence:** Combined user profiles with financial statistics from the data warehouse to derive financial‑health indicators and generate actionable, personalized coaching insights.

#### **2. Intelligent Recommendation Orchestration**

* **Dynamic Decisioning:** Designed logic to determine both the **timing** and **type** of recommendations, deciding whether to nudge users toward MALY products (e.g., savings goals) or relevant third‑party financial services.
* **Hybrid Recommendation System:** Acted as the integration layer between data‑science‑driven recommendation models and the conversational AI, transforming data‑driven outputs into empathetic, coaching‑oriented dialogue.

#### **3. Knowledge & Admin Infrastructure**

* **Internal Admin Web Application:** Designed and built a standalone admin portal enabling non‑technical staff to manage LUNA’s static knowledge base, including product features, financial guidelines, and platform announcements.
* **Dual‑Data Architecture:** Managed a system balancing **dynamic data** (real‑time transactions from the data warehouse) with **static data** (platform content from the admin portal) to maintain accuracy and relevance.

---

### 🛠️ **Tech Stack**

* **AI / LLM:** Gemini, custom LLM orchestration
* **Backend:** FastAPI, Python
* **Data:** Data Warehouse (e.g., BigQuery / Snowflake / Redshift), SQL, MongoDB
* **Architecture:** Event‑driven recommendations, behavioral nudging logic

---

### 💡 **Professional Impact**

* **Personalization:** Shifted the platform from generic alerts to **personalized financial coaching**, significantly increasing engagement with MALY’s financial products.
* **Operational Efficiency:** Reduced engineering overhead for content updates by approximately **80%** through the introduction of the Admin Management Portal.
