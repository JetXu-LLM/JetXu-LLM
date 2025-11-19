### Hi, I'm Jet Xu 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jiantongxu/)
[![Blog](https://img.shields.io/badge/Blog-jetxu--llm.github.io-blue?style=flat-square)](https://jetxu-llm.github.io)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jiantong.xu@foxmail.com)

Today's AI for code is a mile wide and an inch deep. It can write a function, but it can't grasp the architecture. It's stuck seeing the trees, blind to the forest.

My conviction: **True code intelligence doesn't come from analyzing text; it comes from understanding relationships.** The future of AI-powered development will be built on a single source of truth: the **Repository Knowledge Graph**.

---

### The First Proof: From Insight to Impact with LlamaPReview

To validate this thesis, I started with the most painful problem in development: noisy, context-blind AI code reviews. The result is LlamaPReview.

It's not just another reviewer. It's the first application of my graph-based philosophy, using a **Context Retrieval Engine** to find evidence across the entire codebase.

**The market has validated this approach:**
*   🚀 **Trusted by 4,000+ repositories** with over **35,000+ combined stars**.
*   🎯 **Achieved a 61% signal-to-noise ratio**, 3x higher than diff-based tools. **[Read the analysis](https://jetxu-llm.github.io/posts/low-noise-code-review/)**.
*   🐛 **Identified a critical bug in Vanna.ai** (a 20K-star project) that was invisible to human reviewers and other AI tools. **[See the case study](https://jetxu-llm.github.io/posts/beyond-the-diff-llamapreview-catches-critical-bug/)**.

[![Try it](https://img.shields.io/badge/Try_LlamaPReview_in_the_Marketplace-2088FF?logo=github&style=flat-square)](https://jetxu-llm.github.io/LlamaPReview-site/)

---

### The Engine: The Repository Knowledge Graph

LlamaPReview's success is a symptom of a more powerful underlying technology I'm developing. It's not just another RAG; it's a persistent, queryable model of a codebase's soul.

**This is the game-changer:**
*   **It maps everything:** Classes, functions, dependencies, call hierarchies, and even historical change patterns.
*   **It enables deep reasoning:** An AI can now ask questions like, "What are the downstream impacts of changing this API?" or "Find all services that don't adhere to our new retry-logic pattern."
*   **It's the foundation:** My preliminary benchmarks show this graph-based approach improves code understanding by **70%** over traditional methods.

---

### The Vision: An Ecosystem of Architecturally-Aware AI Agents

The Repository Graph is not just for code review. It's a platform for a new generation of AI developers.

Imagine agents that can:
*   **Perform autonomous, large-scale refactoring.**
*   **Automate complex framework migrations.**
*   **Generate architectural diagrams and documentation in real-time.**
*   **Identify security vulnerabilities based on deep data-flow analysis.**

This is the future I'm building. The open-source library below is the first step in creating this ecosystem.

---

### 🛠️ The Foundation: llama-github

[![PyPI](https://img.shields.io/pypi/v/llama-github?style=flat-square)](https://pypi.org/project/llama-github/)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=flat-square)](https://github.com/jetxu-llm/llama-github)

The open-source library that brings repository knowledge to LLMs. It's the first building block for the ecosystem I envision.

```bash
pip install llama-github
```

**[View on GitHub →](https://github.com/jetxu-llm/llama-github)**

---

### 📫 Let's Connect

I'm looking to connect with teams and leaders who are building the future of software development. If you believe that deep, architectural understanding is the next frontier for AI in coding, let's talk.