<div align="center">

# ⚡ GEDENDHAR SIVAKUMAR

### **AI/ML Engineer • Python Developer • AWS Certified**

<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=25&duration=3000&color=00F7FF&center=true&vCenter=true&width=850&lines=Python+%7C+AI%2FML+%7C+Generative+AI;Autonomous+Agents+%7C+LangGraph+%7C+RAG;NLP+%7C+Cloud+Architecture+%7C+AWS;Building+High-Performance+Intelligent+Systems"/>

<br/>

<a href="https://portfolio-gedendhar-s.vercel.app/#home" target="_blank">
  <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>
<a href="https://github.com/Gedendhar-5" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-121013?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/gedendhar-s-23b22a197/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

---

### 🧠 Profile Overview

Results-driven **AI/ML Engineer** and **Python Developer** specializing in enterprise-grade **Generative AI systems**, **Multi-Agent workflows**, and robust **NLP/RAG architectures**. Experienced in deploying containerized solutions on **AWS and Render cloud infrastructures**, building high-throughput document intelligence pipelines, and securing LLM applications through adversarial red-teaming.

</div>

<br/>

---

## 🛠️ Technological Arsenal

<div align="center">

### **💻 Core Tech Stack**
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=python,aws,docker,fastapi,flask,git,github,postgres,mongodb,vscode,render" />
</a>

<br/><br/>

### **🤖 Generative AI & Orchestration**
![](https://img.shields.io/badge/LangGraph-Multi--Agent_Swarms-1C3C3C?style=for-the-badge)
![](https://img.shields.io/badge/LangChain-Chains_%26_LCEL-2C5E8A?style=for-the-badge)
![](https://img.shields.io/badge/RAG_Architecture-Dense_Retrieval-4A154B?style=for-the-badge)
![](https://img.shields.io/badge/LLMs-Llama_3.3_/_GPT--4-FF5722?style=for-the-badge)

### **🧠 AI/ML & Natural Language Processing**
![](https://img.shields.io/badge/NLP-Tokenizers_%26_Embeddings-8A2BE2?style=for-the-badge)
![](https://img.shields.io/badge/Transformers-PyTorch_/_HuggingFace-FF4B4B?style=for-the-badge)
![](https://img.shields.io/badge/RLHF-Feedback_Loops-0A66C2?style=for-the-badge)
![](https://img.shields.io/badge/Prompt_Engineering-Optimization-FF6F00?style=for-the-badge)

### **📂 Vector Search & Document Intelligence**
![](https://img.shields.io/badge/FAISS-Index_Vector_Search-0467DF?style=for-the-badge)
![](https://img.shields.io/badge/Tesseract_OCR-Document_Extraction-4285F4?style=for-the-badge)
![](https://img.shields.io/badge/OpenCV-Image_Preprocessing-5C3EE8?style=for-the-badge)
![](https://img.shields.io/badge/MCP_Workflows-Model_Context_Protocol-3F4F75?style=for-the-badge)

### **☁️ Cloud & Infrastructure**
![](https://img.shields.io/badge/AWS-Amazon_Web_Services-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![](https://img.shields.io/badge/Render-Cloud_Hosting-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![](https://img.shields.io/badge/Docker-Containerization-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### **🚀 AI Development Partners & Large Language Models**
![](https://img.shields.io/badge/Antigravity-Agentic_Co--Pilot-4A154B?style=for-the-badge&logo=google&logoColor=white)
![](https://img.shields.io/badge/Gemini_AI-Google_DeepMind-8E24AA?style=for-the-badge&logo=google-gemini&logoColor=white)
![](https://img.shields.io/badge/Claude-Anthropic-D97706?style=for-the-badge&logo=anthropic&logoColor=white)
![](https://img.shields.io/badge/ChatGPT-OpenAI-10a37f?style=for-the-badge&logo=openai&logoColor=white)
![](https://img.shields.io/badge/Perplexity-Research_Engine-22D3EE?style=for-the-badge&logo=perplexity&logoColor=white)

</div>

<br/>

---

## 🚀 Featured Engineering Projects

<br/>

### 🛡️ 1. GovAgent — Autonomous AI Compliance Auditor
> **Autonomous governance multi-agent swarm that audits LLMs against global regulatory standards.**
*   **Orchestration**: Built a parallel **fan-out / fan-in** state graph using **LangGraph** to process evaluations concurrently across four agents.
*   **Specialist Agents**: Configured Legal (RAG-backed regulations database), Privacy (PII scanning), Bias (toxicity scoring), and Red-Teaming (adversarial jailbreak simulation) nodes.
*   **Vector Database**: Implemented **FAISS** vector indexes over a 40+ policy regulation corpus (EU AI Act, GDPR, NIST, ISO 42001).
*   **Artifact Generation**: Automatically compiles overall compliance scores and risk parameters into a downloadable **AI Compliance Passport (PDF)**.
*   🛠️ *Tech Stack: Python, LangGraph, Groq Cloud (Llama 3.3), FAISS, Streamlit, Docker, FPDF2.*
*   🔗 **[View Project Repository](https://github.com/Gedendhar-5/govagent-compliance-auditor)**

```mermaid
graph LR
    A["⚙️ Ingest Application Config"] --> B["🧭 LangGraph Orchestration"]
    B --> C1["🏛️ Legal Agent (FAISS RAG)"]
    B --> C2["🔒 Privacy Agent (PII Scan)"]
    B --> C3["⚖️ Bias Agent (Toxicity Eval)"]
    B --> C4["🔴 Red-Team Agent (Jailbreak)"]
    C1 & C2 & C3 & C4 --> D["👔 Chief Compliance Officer"]
    D --> E["📄 AI Passport PDF"]
    style B fill:#1c3c3c,stroke:#333,stroke-width:2px,color:#fff
    style D fill:#4a154b,stroke:#333,stroke-width:2px,color:#fff
```

---

### 📊 2. AI-Powered BI Dashboard
> **Automated data analytics suite that cleans data, generates dashboards, extracts insights, and computes forecasts in a single click.**
*   **One-Click Analytics**: Allows users to upload raw Excel or CSV datasets and automatically run end-to-end data cleaning pipelines.
*   **Predictive Modeling**: Computes statistical forecasts and generates interactive visualizations and summaries.
*   🛠️ *Tech Stack: Python, Pandas, Streamlit, Scikit-Learn, Plotly.*
*   🔗 **[View Project Repository](https://github.com/Gedendhar-5/AI-Powered-BI-Dashboard)**

```mermaid
graph LR
    In["Raw Data (CSV/Excel)"] --> Clean["🧹 Auto-Data Cleaning (Pandas)"]
    Clean --> Forecast["📈 Predictive ML Forecasting (Scikit-Learn)"]
    Forecast --> Insights["💡 Insights Generator (GenAI)"]
    Insights --> UI["📊 Live Plotly Dashboard"]
    style Clean fill:#121013,stroke:#333,color:#fff
    style UI fill:#ff4b4b,stroke:#333,color:#fff
```

---

### 🛡️ 3. Journalist Source Protector — AI Document Redaction System
> **Secure document redaction tool designed to protect whistleblowers and sensitive sources.**
*   **PII Masking**: Leveraged advanced NLP Named Entity Recognition (NER) models to locate and mask private entities (names, addresses, locations, emails).
*   **Risk Scoring**: Evaluates the potential security leak level of documents using a risk-based safety metrics matrix.
*   🛠️ *Tech Stack: Python, Transformers, NLP NER, Streamlit, Document Parsing.*
*   🔗 **[View Project Repository](https://github.com/Gedendhar-5/journalist-source-protector-document--redaction)**

```mermaid
graph LR
    Doc["Whistleblower Doc"] --> NER["🔍 Named Entity Recognition (NER)"]
    NER --> Mask["🔒 Token Masking & Redaction"]
    Mask --> Risk["📉 Security Safety Score Assessment"]
    Risk --> Out["📄 Redacted Safe PDF"]
    style NER fill:#8a2be2,stroke:#333,color:#fff
    style Risk fill:#e94560,stroke:#333,color:#fff
```

---

### 🛠️ 4. Claude Skill Set (Master Prompt Formula)
> **Custom Claude capabilities implementing advanced prompt-engineering frameworks for structured generation.**
*   **Framework Implementation**: Implemented the **RCTFCE** (Role, Context, Task, Format, Constraint, Example) prompt engineering framework.
*   **Structured Outputs**: Built optimized prompt templates to enforce deterministic outputs from Anthropic Claude models.
*   🛠️ *Tech Stack: Claude API, System Prompts, Prompt Engineering, JSON Schema.*
*   🔗 **[View Project Repository](https://github.com/Gedendhar-5/master-prompt-formula)**

```mermaid
graph TD
    Raw["User Request"] --> RCTFCE["📐 Apply RCTFCE Engine"]
    RCTFCE --> System["📝 Compile System Message"]
    System --> Inference["🤖 Anthropic Claude Execution"]
    Inference --> Format["🎯 Strict Structured JSON Output"]
    style RCTFCE fill:#46e3b7,stroke:#333,color:#000
    style Format fill:#0467df,stroke:#333,color:#fff
```

---

### 📊 5. AI DevOps Co-Pilot
> **Autonomous AI observability platform for real-time root cause analysis and infrastructure self-healing.**
*   **Telemetry Observability**: Monitors target clusters for logs, metrics, and threshold violations.
*   **Self-Healing**: Automated LLM-driven actions to orchestrate remediation playbooks and recover failing systems.
*   🛠️ *Tech Stack: Python, LangChain, Kubernetes API, Groq, Logging Observability.*
*   🔗 **[View Project Repository](https://github.com/Gedendhar-5/ai-devops-copilot)**

```mermaid
graph LR
    Metric["📡 Cluster Telemetry Logs"] --> Detect["🔍 Anomaly Detection Engine"]
    Detect --> Reason["🧠 LLM Root Cause Analysis (RCA)"]
    Reason --> Recover["🛠️ Remediation Orchestrator"]
    Recover --> Repair["✅ Self-Healing Actions executed"]
    style Reason fill:#1C3C3C,stroke:#333,color:#fff
    style Recover fill:#ff5722,stroke:#333,color:#fff
```

---

### 💬 6. AI Log Analyzer
> **Generative AI log analysis conversational agent for developers and systems engineers.**
*   **Fast API Backend**: Created a lightweight, async API layer using **FastAPI** to feed log inputs into an LLM analysis engine.
*   **Root Cause Analysis (RCA)**: Classifies logs in real-time, extracts trace errors, and provides detailed code fix suggestions.
*   🛠️ *Tech Stack: FastAPI, Groq API (Llama 3), LangChain, Python.*
*   🔗 **[View Project Repository](https://github.com/Gedendhar-5/AI-Log-Analyzer)**

```mermaid
graph LR
    Logs["App Logs Ingest"] --> Fast["⚡ FastAPI Endpoint"]
    Fast --> LC["⚙️ LangChain Extraction Node"]
    LC --> Model["🤖 Llama 3 (Groq API) Analysis"]
    Model --> Suggest["💡 Root Cause + Fix Script"]
    style Fast fill:#00d2ff,stroke:#333,color:#000
    style Model fill:#8a2be2,stroke:#333,color:#fff
```

---

### 🏁 7. F1 Race Prediction ML Model
> **Predictive analytics engine for Formula 1 Grand Prix classification and outcome forecasting.**
*   **Telemetry Processing**: Ingests weather conditions, historical lap times, qualifyings, and driver telemetry attributes.
*   **ML Pipeline**: Built regression and classification models to forecast podium results and race trends.
*   🛠️ *Tech Stack: Python, Pandas, Scikit-Learn, LightGBM, Data Engineering.*
*   🔗 **[View Project Repository](https://github.com/Gedendhar-5/-f1-race-prediction-ml)**

---

### 💼 8. AI Career Co-Pilot
> **Generative AI tool for resume optimization, automated matching, and career positioning.**
*   **RAG Optimization**: Scans resume profiles against job descriptions to suggest custom prompt-based improvements.
*   🛠️ *Tech Stack: Python, OpenAI ChatGPT, LangChain, RAG.*
*   🔗 **[View Project Repository](https://github.com/Gedendhar-5/AI-Career-Copilot)**

<br/>

---

## 💼 Professional Trajectory

### **Geometry Technologies** — *Software Engineer*
*   **Scalable NLP Pipelines**: Architected high-performance natural language processing pipelines in Python to process unstructured text at scale.
*   **Robust Backends**: Developed, tested, and optimized microservices and RESTful API endpoints for core enterprise products.
*   **AWS Infrastructure**: Deployed and managed serverless and containerized applications using Amazon Web Services (AWS) ECS, Lambda, and S3.
*   **Workflow Automation**: Automated internal developer loops and CI/CD procedures, boosting engineering efficiency by 30%.

<br/>

---

## 🏆 Certifications & Achievements

*   🎓 **AWS Certified Solutions Architect – Associate** (Amazon Web Services)
*   📜 **Python Programming** (Google | Coursera)
*   💼 **Agile Methodology Virtual Experience** (JPMorgan Chase)
*   🤖 **Claude in Action** (Anthropic Claude Frameworks)

<br/>

---

## 📊 Git Statistics

<div align="center">

<table border="0">
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=Gedendhar-5&show_icons=true&theme=tokyonight&count_private=true" alt="Gedendhar's GitHub Stats" />
    </td>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gedendhar-5&layout=compact&theme=tokyonight" alt="Top Languages" />
    </td>
  </tr>
</table>

</div>

<br/>

---

<div align="center">

### 🤝 Connect & Collaborate

Let's discuss Multi-Agent Systems, RAG architecture, LLM Security, or Python Backends.

[![LinkedIn Badge](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/gedendhar-s-23b22a197/)
[![Portfolio Badge](https://img.shields.io/badge/-Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-gedendhar-s.vercel.app/#home)

</div>
