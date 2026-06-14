# Kumud Sharma
**ML / AI Engineer · Building intelligent systems, agents, and automation workflows**

[![GitHub](https://img.shields.io/badge/GitHub-winterbeer-181717?style=flat&logo=github)](https://github.com/winterbeer)

---

## About Me

I work at the intersection of AI engineering, agentic systems, and automation — focused on turning real-world problems into intelligent, structured solutions.

My work spans building LLM-powered applications, designing multi-agent workflows, and creating automation pipelines that connect AI capabilities with practical business and technical needs. I am drawn to systems that are not just technically sound but genuinely useful — where AI serves a clear purpose.

This GitHub reflects both my applied project work and my ongoing technical development across AI frameworks, workflow automation, and ML pipelines.

- Strong foundation in **Python**, **LangChain**, **LangGraph**, and **n8n** for building AI-driven workflows
- Hands-on experience with **RAG pipelines**, **vector databases**, and **local LLM deployment** via Ollama
- Practical exposure to **FastAPI** and **Streamlit** for building and exposing AI applications
- Experience in **ML modelling** for prediction, classification, and NLP use cases
- Currently deepening expertise in **multi-agent architectures**, **tool-use patterns**, and **production-grade AI systems**

---

## Experience

### AI & Automation Executive | *(Current)*
Working within an industrial B2B organisation to bring AI and automation into the core of business operations.

My primary initiative is building the **Company Brain** — an internal knowledge and intelligence system designed to centralise business context, surface relevant information, and support decision-making across the organisation. This involves designing the architecture, connecting data sources, and building the retrieval and reasoning layers that make it practically useful.

Beyond that, I build and deploy **no-code and low-code automation workflows** using n8n and similar tools — including:

- **Industrial intelligent agents** that autonomously fetch, filter, and deliver business-relevant news and market information tailored specifically to the company's domain and interests
- Workflow automations that reduce manual effort across internal operations, reporting, and communication
- AI-assisted pipelines that connect external data sources with internal business logic

This role sits at the intersection of AI engineering, workflow design, and practical business execution — focused on making intelligent systems that people in the organisation actually use.

---

## Selected Projects

### 🤱 Sakhi — Maternal Care Assistant
An AI-powered maternal health assistant designed to support pregnant women with accessible health guidance, symptom awareness, and nutrition recommendations.

Built as a modular Python application with a Streamlit frontend, FastAPI backend, and separate AI modules for symptom checking and nutrition advisory. Uses LangChain, ChromaDB, Sentence Transformers, and a local LLM via Ollama. Delivers context-aware responses through a RAG pipeline built on a curated maternal health knowledge base.

**My role:** End-to-end project ownership — problem definition, system architecture, module design, RAG pipeline implementation, and deployment.

[View Repository →](https://github.com/winterbeer/Sakhi--Maternal-Care-Assistant)

---

### 🎯 Ideal Customer Profile Generator
A multi-agent system that generates Ideal Customer Profiles (ICPs) from a plain-English product description. The design goal was a system that makes its own decisions, evaluates its own output, and can course-correct — not just produce plausible-sounding text.

Built on n8n and Groq (Llama 3.3 70B), the pipeline uses seven agents working in sequence and in parallel: a Router that classifies input and generates adaptive instructions for downstream specialists; four parallel specialist agents (Demographic, Behavioral, Psychological, Problem/JTBD); a Synthesizer that merges all analyses into a single coherent ICP; and a Critic that scores output on consistency, specificity, completeness, and actionability. If the critic fails the ICP, a Refinement agent rewrites it using the critic's specific feedback. Final output is a formatted, downloadable HTML report.

**My role:** End-to-end architecture and implementation — agent design, orchestration logic, critic/refinement loop, and output formatting.

[View Repository →](https://github.com/winterbeer/Ideal-Customer-Profile)

---

### 🦠 Disease Outbreak Prediction
An ML model built to predict the likelihood of disease outbreaks using historical and epidemiological data. Focused on surfacing early warning signals to support public health awareness and decision-making.

**My role:** Data preparation, model development, evaluation, and documentation.

---

### 🎬 Movie Recommendation System
A content-based recommendation engine built with Python and NLTK. Processes movie metadata using NLP techniques to surface relevant suggestions based on text similarity and user preferences.

**My role:** End-to-end implementation covering data processing, NLP pipeline, similarity modelling, and interface.

[View Repository →](https://github.com/winterbeer/movie_recommendation_system)

---

## Skills

**Languages & Frameworks:** Python, LangChain, LangGraph, FastAPI, Streamlit  
**AI & ML:** RAG Pipelines, Vector Databases (Chroma), Embeddings, Local LLMs (Ollama), NLTK, Scikit-learn  
**Automation & Workflows:** n8n, REST APIs, Workflow Automation  
**Concepts:** Multi-Agent Systems, Prompt Engineering, Retrieval-Augmented Generation, ML Modelling

---

## Current Direction

I am currently focused on deepening my expertise in **multi-agent system design**, **LangGraph-based orchestration**, and **production deployment of AI applications** — while continuing to build tools that are practically useful and technically rigorous.

My long-term direction is toward building robust AI systems that connect intelligent reasoning, structured workflows, and real-world execution.

---

*Building one agent at a time.*
