<h1 align="center">👋 Hi, I'm Miles Qi Li</h1>
<p align="center">
  🛠️ Staff AI Developer @ Tiptree Advanced Systems | 🎓 Ph.D. in Computer Science, McGill University
  <br>
  🤖 AI Agent Systems · 🛡️ AI Safety & LLM Security · 🧠 LLM Training & Post-training
</p>

---

## 🧠 About Me

I build and secure AI agent systems. At **Tiptree Advanced Systems** I work on the infrastructure that research agents run on: sandboxed code execution, job orchestration across HPC clusters, the credential and access model agents operate under, and deep-research agents with tool access. Before that, I was a postdoctoral researcher at McGill working on LLM security, agent safety evaluation, and data-efficient LLM training.

My research record spans AI agent safety and LLM security (constraint-violation benchmarks, prompt injection, jailbreaks, red teaming), LLM pre-training and post-training, and, earlier, adversarial robustness, interpretability, and malware detection. I care about the same question from both sides: how to make agents capable, and how to know when they go wrong.

---

## 🏗️ What I Build at Tiptree

- 🤝 [**Althea**](https://althea.tiptreesystems.com)  
  An always-on AI research assistant with a persistent agent runtime. I build the runtime it runs on (sandboxed code execution, job orchestration across HPC clusters, and the credential and access model agents operate under) and its deep-research agent.

- 🗺️ [**Lacuna**](https://lacuna.tiptreesystems.com)  
  A research map for machine learning that surfaces under-explored research directions from the literature: directions, papers, authors, and venues. I built its hybrid lexical + semantic search, the agent-facing context APIs, author profile claiming with verified identity, the new-papers feed, the hosted MCP endpoint, and the production database and search-index operations.

- 🔌 [**Lacuna Research MCP**](https://github.com/tiptreesystems/lacuna-research-mcp)  
  Open-source MCP server that gives coding agents and assistants access to Lacuna: search research directions, papers, authors, and venues, and generate research proposals.

- 🖥️ [**tasc-hpc-daemon**](https://pypi.org/project/tasc-hpc-daemon/)  
  PyPI package: a daemon that bridges AI agents to remote HPC compute, so an agent can submit, monitor, and collect jobs on a cluster it does not run on.

---

## 🚀 Research Projects

### 🛡️ Agent Safety & Security

- 🧪 [**ODCV-Bench**](https://github.com/McGill-DMaS/ODCV-Bench)  
  A benchmark for evaluating **outcome-driven constraint violations** in autonomous AI agents: whether agents break explicit rules when doing so helps them reach their goal. The paper reached [#1 on Hacker News](https://news.ycombinator.com/item?id=46954920) in February 2026 (544 points, 366 comments; [ranking history](https://hnrankings.com/46954920/)).

- 🛠️ [**Kam1n0-Community**](https://github.com/McGill-DMaS/Kam1n0-Community)  
  Scalable binary similarity analysis platform for reverse engineering, built with Apache Spark and Cassandra.

- 🧮 [**iffnn**](https://github.com/MilesQLi/iffnn)  
  Interpretable feedforward neural network architecture for tabular data with intrinsic explanations for its predictions.

### 🧠 LLM Training

- 🦙 [**DMaS-LLaMa-Lite-Training-Code**](https://github.com/McGill-DMaS/DMaS-LLaMa-Lite-Training-Code)  
  Complete training pipeline for a 1.7B-parameter LLaMa-based model, optimized for data-efficiency.

- 🔁 [**Incremental-LLM-Training**](https://github.com/McGill-DMaS/Incremental-LLM-Training)  
  Layer-wise incremental LLM training: a novel paradigm to improve compute utilization and training throughput.

### 📁 Personal projects

[**COMPASS-Implementation**](https://github.com/infiniteoptimization/COMPASS-Implementation) (multi-agent system after Google Research's COMPASS, with MCP tools and a FastAPI dashboard) · [**Miles_AI_Collection**](https://github.com/MilesQLi/Miles_AI_Collection) (LLM training and LangChain experiments) · [**Virtual Customer Service Representative**](https://github.com/MilesQLi/VirtualCustomerServiceRepresentative) (LangGraph ReAct + FAISS RAG app) · [**Miles_Data_Science_Collection**](https://github.com/MilesQLi/Miles_Data_Science_Collection) (EDA and modeling on real-world datasets)

---

## 🧰 Tech Stack & Tools

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red?logo=pytorch)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow?logo=huggingface)
![Docker](https://img.shields.io/badge/Docker-Containers-blue?logo=docker)
![Firecracker](https://img.shields.io/badge/Firecracker-microVM%20Sandboxes-orange)
![FastAPI](https://img.shields.io/badge/FastAPI-Services-009688?logo=fastapi)
![Redis](https://img.shields.io/badge/Redis-State-red?logo=redis)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-Hybrid%20Search-005571?logo=elasticsearch)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-336791?logo=postgresql)
![Slurm](https://img.shields.io/badge/Slurm-HPC%20Jobs-lightgrey)
![MCP](https://img.shields.io/badge/MCP-Agent%20Tools-9cf)
![LangChain](https://img.shields.io/badge/LangChain-LLM%20Apps-9cf?logo=langchain)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-BigData-orange?logo=apachespark)
