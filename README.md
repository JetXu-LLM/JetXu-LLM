### Hi, I'm Jet Xu 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jiantongxu/)
[![Blog](https://img.shields.io/badge/Blog-jetxu--llm.github.io-blue?style=flat-square)](https://jetxu-llm.github.io)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jiantong.xu@foxmail.com)

My obsession is solving the **signal-to-noise problem** in AI code review. My conviction is that **code understanding requires graphs, not just embeddings.**

---

### Phase 1: Deep Context Review (Today) — LlamaPReview

[![Active Repos](https://img.shields.io/badge/Active_Repos-4,000+-success?style=flat-square)](https://jetxu-llm.github.io/LlamaPReview-site/)
[![Combined Stars](https://img.shields.io/badge/Combined_Stars-35K+-yellow?style=flat-square)](https://jetxu-llm.github.io/LlamaPReview-site/)
[![Try it](https://img.shields.io/badge/GitHub-Marketplace-2088FF?logo=github&style=flat-square)](https://github.com/marketplace/llamapreview)

I built LlamaPReview to prove that evidence-based AI can find bugs that humans miss. It uses a **Context Retrieval Engine** to analyze how changes ripple across a codebase, moving beyond simple `diff` analysis.

**Key Achievements & Evidence:**
*   🎯 **61% Signal-to-Noise Ratio:** Achieved a 3x higher signal rate compared to traditional AI reviewers. **[Read the data-driven analysis](https://jetxu-llm.github.io/posts/low-noise-code-review/)**.
*   🐛 **Critical Bug in Vanna.ai:** Caught a transaction commit failure in a 20K-star project that was invisible in the diff. **[Read the full case study](https://jetxu-llm.github.io/posts/beyond-the-diff-llamapreview-catches-critical-bug/)**.
*   🚀 **Validated at Scale:** Trusted by over 4,000 repositories.

**[Try LlamaPReview →](https://jetxu-llm.github.io/LlamaPReview-site/)**

---

### The Endgame: From Review to Autonomous Agents

LlamaPReview is the first step. My ultimate goal is to build autonomous agents that can independently accomplish complex engineering tasks. This requires a shift from context retrieval to true architectural reasoning.

#### Phase 2: Architectural Reasoning (The Future) — Repository Graph RAG

This is the next evolution. Instead of ad-hoc searches, this phase involves building a persistent **Repository Knowledge Graph**.

*   **How it works:** Maps the entire codebase—classes, methods, dependencies, and call graphs—into a traversable structure.
*   **The Leap:** Enables an AI to reason about architectural impacts, understand complex dependency chains, and perform tasks like "refactor this service to use the new authentication module."
*   **Early Results:** My PoCs show a **70% improvement** in code understanding benchmarks over traditional RAG.

This is the foundational technology for the next generation of AI developer tools.

---

### 🛠️ Open Source Foundation: llama-github

[![PyPI](https://img.shields.io/pypi/v/llama-github?style=flat-square)](https://pypi.org/project/llama-github/)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=flat-square)](https://github.com/jetxu-llm/llama-github)

The engine powering my vision. A Python library for production-grade GitHub knowledge retrieval, built for AI agents.

```bash
pip install llama-github
```
```python
from llama_github import GithubRAG

# The context retrieval module for future automated development systems
github_rag = GithubRAG(github_token="...", openai_key="...")
context = github_rag.retrieve_context("How to implement async context managers?")
```
**[View on GitHub →](https://github.com/jetxu-llm/llama-github)**

---

### 💻 Tech Stack

| **AI/ML** | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LangChain](https://img.shields.io/badge/-LangChain-121212?style=flat-square) ![Hugging Face](https://img.shields.io/badge/-HF-FFD21E?style=flat-square&logo=huggingface&logoColor=black) |
| **Data & Infra** | ![ArangoDB](https://img.shields.io/badge/-ArangoDB-DDE072?style=flat-square&logo=arangodb&logoColor=black) ![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |

---

### 📫 Let's Connect

I'm looking to connect with teams who are serious about building the next generation of AI developer tools.

- 💼 [LinkedIn](https://www.linkedin.com/in/jiantongxu/) — For my professional background and enterprise experience.
- 🐙 [GitHub](https://github.com/jetxu-llm) — You're here. This is where I build my vision.
- 📝 [Blog](https://jetxu-llm.github.io) — For technical deep dives on Graph RAG and AI architecture.

---
*Building the future of code intelligence, one graph at a time.* 🦙
