<h1 align="center">Hi, I'm Vamsi 👋</h1>

<p align="center">
  <b>GenAI / Applied AI Engineer · PhD Researcher</b><br>
  Heinz Nixdorf Chair for Distributed Information Systems · Friedrich-Schiller-Universität Jena<br>
  📍 Friedberg, Hessen, Germany
</p>

<p align="center">
  <a href="https://vamsi-kommineni.github.io/"><img src="https://img.shields.io/badge/Website-0d1626?style=for-the-badge&logo=aboutdotme&logoColor=white" alt="Website"></a>
  <a href="https://www.linkedin.com/in/vkk99"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://scholar.google.com/citations?user=ZEz2nk4AAAAJ"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://orcid.org/0000-0001-6168-3085"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="mailto:vamsik.kommineni@outlook.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### About me

I build generative AI systems and take them to production: LLM applications, RAG pipelines and AI agents, alongside computer vision and vision-language models. Most recently I was **Founding AI Lead at [Nixi AI](https://www.nixiai.ai/de)**, an EXIST-funded AI startup in healthcare, where I built and deployed LLM, RAG and agentic services on Google Cloud and Azure, plus pipelines for German speech-to-text fine-tuning, document classification, GDPR-aware anonymization and document generation. I'm a PhD candidate in computer science at FSU Jena (expected 2026), working on LLM-based information extraction, knowledge graph construction and computer vision.

- 🔭 I work on **LLMs, RAG and AI agents**, **knowledge graph / ontology construction**, **computer vision and vision-language models**, and **speech-to-text**
- 🌱 Currently exploring **LLM observability and evaluation** and **agentic systems**
- 💞️ Open to collaborating on **open-source GenAI tooling**, **knowledge graph research** and **reproducible ML**
- 📫 Reach me at **vamsik.kommineni@outlook.com** or on [LinkedIn](https://www.linkedin.com/in/vkk99)
- ⚡ 7+ years in ML and deep learning, LLMs since 2023, in production since 2025; peer-reviewed in *PeerJ Computer Science* and at *SEMANTiCS*

---

### 🚀 Selected projects

| Project | Description | Stack |
|---|---|---|
| **[Inagecas](https://github.com/Vamsi-Kommineni/Inagecas)** | AI customer-support pipeline that answers tickets only from a company's approved documentation, and refuses, asks a clarifying question or escalates to a human when it isn't sure. Policy gate (PII and prompt-injection guardrails, intent routing), hybrid dense + BM25 retrieval with cross-encoder reranking, answer validation with an LLM judge, screenshot reading, OpenTelemetry tracing and a regression eval harness. Hosted models with local Ollama fallbacks. | RAG · Guardrails · Hybrid retrieval · Reranking · Vision-language (ling-3.0-flash-vl) · FastAPI · Qdrant · LiteLLM · OpenTelemetry |
| **[llm-logs](https://github.com/Vamsi-Kommineni/LLM_Logs)** | Python library that records every LLM call (prompts, completions, real parameters, latency, tokens, errors, trace context) to JSONL, SQLite or OpenTelemetry. About 0.1 ms per call, all slow work on a background thread, credentials kept out by construction. Adapters for Groq, OpenAI and Anthropic. v2 (2026) developed with Claude Code. | LLM observability · OpenTelemetry · Python library |
| **[Automatic KG & ontology construction](https://github.com/fusion-jena/automatic-KG-creation-with-LLM)** | Pipeline that builds ontologies and knowledge graphs from text with LLMs, with a focus on reproducibility. · [Paper](https://arxiv.org/abs/2403.08345) | Knowledge graphs · Ontology · LLMs |
| **[Multi-LLM information retrieval with RAG](https://github.com/fusion-jena/information-retrieval-using-multiple-LLM-and-RAG)** | Ensembles multiple open-source LLMs with RAG to extract deep learning methodologies from hundreds of research articles. · [Paper](https://doi.org/10.7717/peerj-cs.3204) | RAG · LLM ensemble · Information retrieval |
| **[Agentic competency-question generation](https://github.com/fusion-jena/Agentic-CQ-Generation)** | Agentic, retrieval-augmented pipeline that generates, validates and consolidates competency questions to support KG / ontology development, applied to the copolymer domain. · [Poster paper, SEMANTiCS 2026](https://2026-eu.semantics.cc/page/p&d-detail?page=25) | AI agents · RAG · Knowledge graphs |

---

### 📝 Selected publications

- **Agentic Competency Question Generation for Copolymer Domain Ontologies**, poster paper, *SEMANTiCS* (2026) · [Page](https://2026-eu.semantics.cc/page/p&d-detail?page=25)
- **Multi-LLM information retrieval pipeline for extracting deep learning methodologies in biodiversity research**, *PeerJ Computer Science* (2025) · [DOI](https://doi.org/10.7717/peerj-cs.3204)
- **Evaluating the method reproducibility of deep learning models in biodiversity research**, *PeerJ Computer Science* (2025) · [DOI](https://doi.org/10.7717/peerj-cs.2618)
- **Towards the Automation of Knowledge Graph Construction using Large Language Models**, NLP4KGC @ *SEMANTiCS* (2024) · [PDF](https://ceur-ws.org/Vol-3874/paper2.pdf)

📚 Full list on [my website](https://vamsi-kommineni.github.io/publications/) and [Google Scholar](https://scholar.google.com/citations?user=ZEz2nk4AAAAJ).

---

### 🛠️ Tools & technologies

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud">
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logoColor=white" alt="Microsoft Azure">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

`LLMs & RAG`&nbsp;&nbsp;`AI agents (LangGraph)`&nbsp;&nbsp;`Knowledge graphs / ontologies`&nbsp;&nbsp;`Computer vision (detection, segmentation, CLIP, Qwen vlm)`&nbsp;&nbsp;`Speech-to-text (ASR)`&nbsp;&nbsp;`LLM observability & evaluation`&nbsp;&nbsp;`Reproducible ML`

---
