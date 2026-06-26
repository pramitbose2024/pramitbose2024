# Pramit Kumar Bose

**AI Engineer & NLP Researcher** — Applied Systems × Architectural Research

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](#)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](#)
[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)](#)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](#)
[![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](#)

---

## About

I build and ship AI systems, and I dig into the architectural reasoning behind them. My work spans applied NLP engineering — RAG pipelines, conversational memory, evaluation frameworks — and research into legal AI and judicial document intelligence, where I'm interested in how architectural decisions (sequence models vs. retrieval-augmented generation, hierarchical labeling schemes) translate into measurable differences in accuracy, latency, and reliability.

I'm a final-year B.Tech Computer Science student at Techno India University, currently working as a Research Intern at IIEST Shibpur on NLP for the Indian judicial system. Open to AI Engineer and research-adjacent roles where I can both build production systems and study why they perform the way they do.

---

## Research Interests

- **Legal NLP & Judicial Document Intelligence** — rhetorical role labeling, petition analysis, and outcome prediction for Indian court case documents
- **Retrieval-Augmented Generation** — retrieval strategy design (MMR, hybrid retrieval), context grounding, and hallucination mitigation
- **Evaluation Methodology for LLM Systems** — LLM-as-judge frameworks, retrieval accuracy and groundedness benchmarking
- **Comparative Architecture Studies** — sequence models (RNN/LSTM) vs. transformer-based retrieval architectures for QA and language generation
- **Low-Resource & Domain-Adapted NLP** — adapting general-purpose architectures to specialized corpora (legal text, enterprise policy documents)

---

## Research Experience

### Research Intern — IIEST Shibpur
*January 2026 – Present · Supervised by Prof. Asit Kumar Das*

- Researching NLP and Deep Learning applications for judicial document intelligence and the Indian legal system
- Applying Rhetorical Role Labeling via a Hierarchical BiLSTM-CRF architecture for legal document classification, petition analysis, and outcome dependency prediction
- Annotated and structured 500+ Indian court case documents to support predictive judicial analytics

---

## Featured Projects

### Architecture Benchmarking: RNN vs. RAG for Question Answering
*Ongoing comparative study*

Two QA systems built on fundamentally different paradigms — a SimpleRNN-based architecture and a retrieval-augmented pipeline — evaluated against each other to understand how architectural choice affects accuracy, latency, and answer reliability for QA tasks.

#### [HR Policy RAG Chatbot](#)
`Python` `LangChain` `ChromaDB` `Groq (Llama 3.3-70B)` — *May–June 2026*

- Production-grade RAG pipeline for enterprise HR queries, combining MMR-based diverse retrieval with 800-token document chunking (150-token overlap)
- Custom conversational memory module with LLM-driven query rewriting to resolve multi-turn context (e.g., pronoun references across follow-ups)
- Guardrailed prompt layer enforcing strict context-grounding and role-specific answer matching to prevent hallucination
- Built a dedicated evaluation framework (golden test set + LLM-as-judge scoring): **94.7% top-K retrieval accuracy**, **4.45/5 average groundedness**, sub-1-second average latency across 20 benchmark queries

#### [AI-Powered Question Answering Engine](#)
`Python` `PyTorch` `NumPy` `Pandas` — *September 2025*

- SimpleRNN-based QA architecture with embedding and fully connected layers
- Custom preprocessing pipeline: tokenization, vocabulary construction (250+ tokens across 130+ QA pairs), text-to-index conversion — ~20% improvement in preprocessing efficiency
- Confidence threshold mechanism (≥70%) to filter unreliable predictions, reducing low-confidence outputs by ~28%
- Training loss reduced 45% over 20 epochs, corresponding to a perplexity of ~5.6

---

### [Context-Aware Text Generation Engine](#)
`Python` `PyTorch` `NumPy` — *October–November 2025*

LSTM-based next-word prediction system designed to learn sequential language patterns from a limited corpus and produce coherent multi-word continuations.

- Custom end-to-end NLP pipeline: tokenization, vocabulary construction (220+ tokens from a 340-word corpus), sequence padding
- Optimized PyTorch Dataset/DataLoader implementation — ~25% improvement in training throughput
- Training loss reduced 35% over 50 epochs, corresponding to a perplexity of ~3.8, generating coherent 10–15 word continuations

---

## Skills

| Category | Technologies |
|---|---|
| Languages | Python, C++ |
| ML / DL Frameworks | PyTorch, TensorFlow, Keras, Scikit-learn, Hugging Face Transformers |
| Generative AI & Agentic Systems | LangChain, RAG pipelines (ChromaDB, FAISS) |
| Data & Analytics | NumPy, Pandas, SQL |
| Tools & Platforms | VS Code, Jupyter Notebook, Google Colab, Kaggle, Streamlit |
| Research Areas | NLP, Legal AI, RAG system evaluation, sequence model architectures, Reinforcement Learning |

---

## Education

**B.Tech, Computer Science and Engineering**
Techno India University, Kolkata — Nov 2021 – Aug 2025 · CGPA 7.35

---

## Connect

- LinkedIn: [linkedin.com/in/pramit-bose-4ba56a209](https://www.linkedin.com/in/pramit-bose-4ba56a209/)
- Email: pramitbose565@gmail.com
