### Hi, I'm Jet Xu 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jiantongxu/)
[![My Blog](https://img.shields.io/badge/Blog-jetxu--llm.github.io-blue?style=flat-square)](https://jetxu-llm.github.io)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jiantong.xu@foxmail.com)

I build **AI systems that understand code at scale**. My work is centered on **Repository Graph RAG** and creating evidence-based code intelligence tools that developers actually trust.

> My core belief: **Code understanding requires graphs, not just embeddings.**

---

### 🚀 Featured Product: LlamaPReview
**Evidence-Based AI Code Review that finds bugs human reviewers miss.**

[![Active Repos](https://img.shields.io/badge/Active_Repos-4,000+-success?style=flat-square)](https://github.com/marketplace/llamapreview)
[![Combined Stars](https://img.shields.io/badge/Combined_Stars-35K+-yellow?style=flat-square)](https://github.com/marketplace/llamapreview)
[![GitHub Marketplace](https://img.shields.io/badge/View_on-Marketplace-2088FF?logo=github&style=flat-square)](https://github.com/marketplace/llamapreview)

Most AI tools only see the `diff`. **LlamaPReview analyzes the entire repository as a graph**, understanding how changes ripple through your system to catch critical, cross-file bugs.

````artifact
id: graph-rag-diagram
name: LlamaPReview's Core Logic
type: mermaid
content: |-
  sequenceDiagram
      participant User as User
      participant PR as GitHub PR
      participant LlamaPReview as LlamaPReview Engine
      participant CodeGraph as Repository Knowledge Graph

      User->>PR: Pushes new commit
      PR-->>LlamaPReview: Triggers review
      LlamaPReview->>CodeGraph: Analyzes changed code
      LlamaPReview->>CodeGraph: Traverses graph to find related, unchanged code (e.g., callers)
      CodeGraph-->>LlamaPReview: Returns deep context (e.g., `src/vanna/flask/__init__.py`)
      LlamaPReview->>LlamaPReview: Finds bug (e.g., Transaction Commit Failure)
      LlamaPReview-->>PR: Posts high-signal, evidence-backed comment
````
*This diagram shows how LlamaPReview caught a critical bug in a 20K-star project that was invisible in the diff. [Read the full story here](https://jetxu-llm.github.io/posts/beyond-the-diff-llamapreview-catches-critical-bug/).*

---

### 🛠️ The Foundation: llama-github
[![PyPI](https://img.shields.io/pypi/v/llama-github?style=flat-square)](https://pypi.org/project/llama-github/)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=flat-square)](https://github.com/jetxu-llm/llama-github)

The open-source engine powering my vision. A Python library for production-grade GitHub knowledge retrieval, built for AI agents.

```bash
pip install llama-github
```
```python
from llama_github import GithubRAG

# The context retrieval module for future automated development systems
github_rag = GithubRAG(github_token="...", openai_key="...")
context = github_rag.retrieve_context("How to implement async context managers?")
```
[**View on GitHub →**](https://github.com/jetxu-llm/llama-github)

---

### 💻 My Tech Stack

| Category | Technologies |
| :--- | :--- |
| **AI / ML** | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LangChain](https://img.shields.io/badge/-LangChain-121212?style=flat-square) ![Hugging Face](https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) |
| **Data & Infra** | ![ArangoDB](https://img.shields.io/badge/-ArangoDB-DDE072?style=flat-square&logo=arangodb&logoColor=black) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) |
| **Core** | ![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |

---

### 🌟 My Vision

My goal is to build **autonomous AI agents that can accomplish complex coding tasks**.

This requires moving beyond simple RAG and building systems that combine:
- **Repository Graph RAG** for deep architectural reasoning.
- **Multi-Agent Orchestration** for intelligent task allocation.
- **Seamless Tool Integration** for file editing, testing, and version control.

LlamaPReview is the first step. The ultimate vision is an AI-driven development loop where agents intelligently retrieve context and autonomously execute development tasks, with human oversight.

---

### 📫 Get in Touch

I'm always open to discussing **Graph RAG architectures**, **AI-driven development**, and **collaboration opportunities**.

- 💼 **LinkedIn**: [For my professional background and enterprise experience](https://www.linkedin.com/in/jiantongxu/)
- 🐙 **GitHub**: You are here. This is where I build.
- 📝 **Blog**: [Where I share deep dives and benchmarks](https://jetxu-llm.github.io)
