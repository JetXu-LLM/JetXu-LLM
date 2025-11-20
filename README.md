### Hi, I'm Jet Xu 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jiantongxu/)
[![Blog](https://img.shields.io/badge/Blog-Engineering_Strategy-blue?style=flat-square)](https://jetxu-llm.github.io)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jiantong.xu@foxmail.com)

> **"The future of AI coding isn't just larger context windows—it's smarter context retrieval."**

I am an architect solving the **"Context Precision"** problem in AI software engineering.

While others focus on stuffing more code into an LLM, my focus is on **Repository Graph RAG**—building the "GPS" for codebases. My goal is to enable AI to navigate complex, cross-module dependencies and understand architectural impact with **surgical precision and minimal token usage**.

---

### 1. The Proof of Concept: LlamaPReview
**High-Precision Code Review via Contextual Retrieval**

I built LlamaPReview to prove that **less is more**: by retrieving only the *relevant* dependency graph, we can outperform massive context windows.

[![Active Repos](https://img.shields.io/badge/Active_Repos-4,000+-success?style=flat-square)](https://jetxu-llm.github.io/LlamaPReview-site/)
[![Combined Stars](https://img.shields.io/badge/Combined_Stars-35K+-yellow?style=flat-square)](https://jetxu-llm.github.io/LlamaPReview-site/)

*   **The Metric:** Achieved a **61% Signal-to-Noise Ratio** (3x industry average) by filtering out irrelevant code noise.
*   **The Evidence:** Caught a critical transaction bug in **Vanna.ai** (20K stars) that required tracing logic across multiple hidden modules—something standard "diff-based" AI missed entirely.
*   **The Product:** A validated SaaS solution trusted by 4,000+ repositories.

👉 **[Visit Product Site](https://jetxu-llm.github.io/LlamaPReview-site/)** | 📊 **[Read the Signal-to-Noise Analysis](https://jetxu-llm.github.io/posts/low-noise-code-review/)**

---

### 2. The Foundation: llama-github
**The Retrieval Infrastructure Layer**

To build a graph, you first need high-fidelity data. I open-sourced the retrieval engine that powers my experiments.

[![PyPI](https://img.shields.io/pypi/v/llama-github?style=flat-square)](https://pypi.org/project/llama-github/)

*   **Role:** A production-grade library designed to fetch and structure GitHub data specifically for RAG pipelines.
*   **Capability:** Bridges the gap between raw Git objects and AI-ready context.

```python
from llama_github import GithubRAG
# Efficiently retrieve cross-module context without cloning the entire repo
context = github_rag.retrieve_context("How does the payment service impact the user schema?")
```

👉 **[View on GitHub](https://github.com/jetxu-llm/llama-github)**

---

### 3. The Vision: Repository Graph RAG
**Occupying the "Code Understanding" Ecological Niche**

LlamaPReview was just the first application. My long-term strategy is to build the definitive **Repository Knowledge Graph** that serves as the backend for all autonomous coding agents.

*   **The Problem:** Flat text search (Standard RAG) loses the *relationships* between classes, methods, and data flows.
*   **The Solution:** A traversable graph that allows LLMs to "hop" through dependencies.
*   **The Value:**
    *   **Token Efficiency:** Solves the problem with 5% of the tokens required by full-context approaches.
    *   **Impact Analysis:** Instantly identifies how a change in `Module A` breaks `Module Z` without reading the files in between.
    *   **Scalability:** The only viable path for AI to understand million-line monoliths.

---

### 📚 Strategic Insights

I document my research on defining the next generation of AI architecture.

*   **[Case Study: Catching the "Invisible" Bug](https://jetxu-llm.github.io/posts/beyond-the-diff-llamapreview-catches-critical-bug/)** — *Real-world evidence: How we found a critical logic error in a 20k-star repo that standard "Diff-based" AI missed entirely.*
*   **[The Signal-to-Noise Ratio in AI Code Review](https://jetxu-llm.github.io/posts/low-noise-code-review/)** — *A new evaluation framework: Why simply increasing context window size often leads to lower quality reviews.*
*   *(Coming Soon)* **The Inconsistency Problem** — *Why the same AI tool works perfectly on Monday but fails on Tuesday: A deep dive into "Context Instability."*
*   *(Coming Soon)* **The End of Guesswork: Repository Graph RAG** — *Moving beyond probabilistic search to deterministic, graph-based dependency analysis for 100% consistent context.*

---

### 💻 Tech Stack

| **Core Intelligence** | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LangChain](https://img.shields.io/badge/-LangChain-121212?style=flat-square) ![Hugging Face](https://img.shields.io/badge/-HF-FFD21E?style=flat-square&logo=huggingface&logoColor=black) |
| **Graph & Data** | ![ArangoDB](https://img.shields.io/badge/-ArangoDB-DDE072?style=flat-square&logo=arangodb&logoColor=black) ![Neo4j](https://img.shields.io/badge/-Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white) ![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) |

---

### 📫 Let's Connect

I am building the infrastructure that will power the next decade of AI development tools.

- 💼 [LinkedIn](https://www.linkedin.com/in/jiantongxu/)
- 📝 [Blog](https://jetxu-llm.github.io)

---
*Building the GPS for the world's code.*
