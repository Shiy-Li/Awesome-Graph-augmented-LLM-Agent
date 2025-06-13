# Awesome-Graph4Agent-Systems
 [![Awesome](https://awesome.re/badge.svg)](https://github.com/RManLuo/Awesome-LLM-KG) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
  ![](https://img.shields.io/github/last-commit/Shiy-Li/Awesome-Graph4Agent-Systems?color=green) 
 ![](https://img.shields.io/badge/PRs-Welcome-red)
 ![](https://img.shields.io/github/stars/Shiy-Li/Awesome-Graph4Agent-Systems?color=yellow)
![](https://img.shields.io/github/forks/Shiy-Li/Awesome-Graph4Agent-Systems?color=lightblue) 

A curated list of awesome papers and resources on leveraging graph structures / algorithm to enhance LLM-based Agent Systems.

## 🗺️ Table of Contents

- [Single Agent](#👤-single-agent)
  - [🧠 Decision Making](#🧠-decision-making)
  - [💾 Storage](#💾-storage)
  - [🔀 LLM Selection & Routing](#🔀-llm-selection--routing)
  - [🛠️ Tool Management](#🛠️-tool-management)
- [Multi Agent](#👥-multi-agent)
  - [🕸️ Workflow Design](#🕸️-workflow-design)
  - [⚡ Efficiency](#⚡-efficiency)
  - [🛡️ Safety](#🛡️-safety)
  - [📚 Knowledge-enhanced Collaboration](#📚-knowledge-enhanced-collaboration)
  - [✨ Others](#✨-others)

---

## 👤 Single Agent

### 🧠 Decision Making
- AFLOW: AUTOMATING AGENTIC WORKFLOW GENERATION (ICLR, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.10762) 💻 [[code]](https://github.com/FoundationAgents/AFlow)
- Tree of Thoughts: Deliberate Problem Solving with Large Language Models (NeurIPS, 2023) 📄 [[paper]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/271db9922b8d1f4dd7aaef84ed5ac703-Abstract-Conference.html) 💻 [[code]](https://github.com/princeton-nlp/tree-of-thought-llm)
- Plan-over-Graph: Towards Parallelable LLM Agent Schedule (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.14563) 💻 [[code]](https://github.com/zsq259/Plan-over-Graph)
- Graphormer-Guided Task Planning: Beyond Static Rules with LLM Safety Perception (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.06866) 💻 [[code]](https://github.com/hwj20/GGTP)
- Can Graph Learning Improve Planning in LLM-based Agents? (NeurIPS, 2024) 📄 [[paper]](https://arxiv.org/abs/2405.19119) 💻 [[code]](https://github.com/WxxShirley/GNN4TaskPlan)
- LocAgent: Graph-Guided LLM Agents for Code Localization (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.09089) 💻 [[code]](https://github.com/gersteinlab/LocAgent)
- VFlow: Discovering Optimal Agentic Workflows for Verilog Generation (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2504.03723)
- Beyond Outlining: Heterogeneous Recursive Planning for Adaptive Long-form Writing with Language Models (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.08275) 💻 [[code]](https://github.com/principia-ai/WriteHERE)
- Benchmarking Agentic Workflow Generation (ICLR, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.07869) 💻 [[code]](https://github.com/zjunlp/WorfBench)
- Graph-Augmented Reasoning: Evolving Step-by-Step Knowledge Graph Retrieval for LLM Reasoning (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.01642)

### 💾 Storage
- Synergizing LLM Agents and Knowledge Graph for Socioeconomic Prediction in LBSN (arxiv, 2024) 📄 [[paper]](https://arxiv.org/abs/2411.00028)
- A-MEM: Agentic Memory for LLM Agents (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.12110) 💻 [[code]](https://github.com/WujiangXu/AgenticMemory)
- AriGraph: Learning Knowledge Graph World Models with Episodic Memory for LLM Agents (arxiv, 2024) 📄 [[paper]](https://arxiv.org/abs/2407.04363) 💻 [[code]](https://github.com/AIRI-Institute/AriGraph)
- GraphReader: Building Graph-based Agent to Enhance Long-Context Abilities of Large Language Models (EMNLP, 2024) 📄 [[paper]](https://arxiv.org/abs/2406.14550)

### 🔀 LLM Selection & Routing
- SMOOTHIE: Label Free Language Model Routing (NeurIPS, 2024) 📄 [[paper]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/e6b57a990462df5afa58d64ce2709db9-Abstract-Conference.html) 💻 [[code]](https://github.com/HazyResearch/smoothie)
- GRAPHROUTER: A GRAPH-BASED ROUTER FOR LLM SELECTIONS (ICLR, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.03834) 💻 [[code]](https://github.com/ulab-uiuc/GraphRouter)

### 🛠️ Tool Management
- TOOLFLOW: Boosting LLM Tool-Calling Through Natural and Coherent Dialogue Synthesis (NAACL, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.18447)
- SciToolAgent: A Knowledge Graph-Driven Scientific Agent for Multi-Tool Integration (preprint, 2025) 📄 [[paper]](https://doi.org/10.21203/rs.3.rs-5610718/v1) 💻 [[code]](https://github.com/HICAI-ZJU/SciToolAgent)
- Toolnet: Connecting large language models with massive tools via tool graph (arxiv, 2024) 📄 [[paper]](https://arxiv.org/abs/2403.00839)

---

## 👥 Multi Agent

### 🕸️ Workflow Design
- DynTaskMAS: A Dynamic Task Graph-driven Framework for Asynchronous and Parallel LLM-based Multi-Agent Systems (ICAPS, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.07675)
- GPTSwarm: Language Agents as Optimizable Graphs (ICML, 2024) 📄 [[paper]](https://arxiv.org/abs/2402.16823) 💻 [[code]](https://github.com/metauto-ai/gptswarm)
- GRAPHAGENT: AGENTIC GRAPH LANGUAGE ASSISTANT (arxiv, 2024) 📄 [[paper]](https://arxiv.org/abs/2412.17029) 💻 [[code]](https://github.com/HKUDS/GraphAgent)
- G-Designer: Architecting Multi-agent Communication Topologies via Graph Neural Networks (ICML, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.11782) 💻 [[code]](https://github.com/yanweiyue/GDesigner)
- HETEROGENEOUS SWARMS: Jointly Optimizing Model Roles and Weights for Multi-LLM Systems (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.04510)
- FLOW: MODULARIZED AGENTIC WORKFLOW AUTOMATION (ICLR, 2025) 📄 [[paper]](https://openreview.net/pdf?id=sLKDbuyq99) 💻 [[code]](https://github.com/tmllab/2025_ICLR_FLOW)
- ReSo: A Reward-driven Self-organizing LLM-based Multi-Agent System for Reasoning Tasks (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.02390) 💻 [[code]](https://github.com/hengzzzhou/ReSo)
- LLM-mediated Dynamic Plan Generation with a Multi-Agent Approach (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2504.01637)
- Scaling Large Language Model-based Multi-Agent Collaboration (ICLR, 2025) 📄 [[paper]](https://arxiv.org/abs/2406.07155) 💻 [[code]](https://github.com/OpenBMB/ChatDev/tree/macnet)
- GNNs as Predictors of Agentic Workflow Performances (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.11301) 💻 [[code]](https://github.com/youngsoul0731/Flora-Bench)
- RESEARCHTOWN: SIMULATOR OF HUMAN RESEARCH COMMUNITY (ICML, 2025) 📄 [[paper]](https://arxiv.org/abs/2412.17767) 💻 [[code]](https://github.com/ulab-uiuc/research-town)
- AGENTNET- DECENTRALIZED EVOLUTIONARY COORDINATION FOR LLM-BASED MULTI-AGENT SYSTEMS (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2504.00587)
- Learning to Be A Doctor: Searching for Effective Medical Agent Architectures (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2504.11301)
- Multi-agent Architecture Search via Agentic Supernet (ICML, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.04180) 💻 [[code]](https://github.com/bingreeky/MaAS)
- EvoFlow: Evolving Diverse Agentic Workflows On The Fly (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.07373)

### ⚡ Efficiency
- Enhancing Multi-Agent Systems via Reinforcement Learning with LLM-based Planner and Graph-based Policy (ICRA, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.10049)
- CUT THE CRAP: AN ECONOMICAL COMMUNICATION PIPELINE FOR LLM-BASED MULTI-AGENT SYSTEMS (ICLR, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.02506) 💻 [[code]](https://github.com/yanweiyue/AgentPrune)
- AgentDropout: Dynamic Agent Elimination for Token-Efficient and High-Performance LLM-Based Multi-Agent Collaboration (ACL, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.18891) 💻 [[code]](https://github.com/wangzx1219/AgentDropout)
- A Dynamic LLM-Powered Agent Network for Task-Oriented Agent Collaboration (COLM, 2024) 📄 [[paper]](https://openreview.net/pdf?id=XII0Wp1XA9) 💻 [[code]](https://github.com/SALT-NLP/DyLAN)

### 🛡️ Safety
- G-Safeguard: A Topology-Guided Security Lens and Treatment on LLM-based Multi-agent Systems (ACL, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.11127) 💻 [[code]](https://github.com/wslong20/G-safeguard)
- NetSafe: Exploring the Topological Safety of Multi-agent Network (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.15686) 💻 [[code]](https://anonymous.4open.science/r/NetSafe-B726/README.md)
- CORBA: Contagious Recursive Blocking Attacks on Multi-Agent Systems Based on Large Language Models (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.14529) 💻 [[code]](https://github.com/zhrli324/Corba)
- AgentSafe: Safeguarding Large Language Model-based Multi-agent Systems via Hierarchical Data Management (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.04392) 💻 [[code]](https://github.com/junyuanM/Agentsafe)

### 📚 Knowledge-enhanced Collaboration
- EduMAS: A Novel LLM-Powered Multi-Agent Framework for Educational Support (BigData, 2024) 📄 [[paper]](https://ieeexplore.ieee.org/abstract/document/10826103/)
- LLM-Powered Decentralized Generative Agents with Adaptive Hierarchical Knowledge Graph for Cooperative Planning (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.05453) 💻 [[code]](https://happyeureka.github.io/damcs/)
- SciAgents: Automating Scientific Discovery Through Bioinspired Multi‐Agent Intelligent Graph Reasoning (Advanced Materials, 2024) 📄 [[paper]](https://advanced.onlinelibrary.wiley.com/doi/full/10.1002/adma.202413523) 💻 [[code]]()

### ✨ Others
- MA-GTS: A Multi-Agent Framework for Solving Complex Graph Problems in Real-World Applications (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.18540) 💻 [[code]](https://github.com/ZIKEYUAN/MA-GTS)
- GraphEval: A Lightweight Graph-Based LLM Framework for Idea Evaluation (ICLR, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.12600) 💻 [[code]](https://github.com/ulab-uiuc/GraphEval)
- Talk structurally, act hierarchically: A collaborative framework for llm multi-agent systems (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.11098) 💻 [[code]](https://github.com/sony/talkhier)
- Topological Structure Learning Should Be A Research Priority for LLM-Based Multi-Agent Systems (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2505.22467)
- AgentCoord: Visually Exploring Coordination Strategy for LLM-based Multi-Agent Collaboration (arxiv, 2024) 📄 [[paper]](https://arxiv.org/abs/2404.11943)
- GUARDIAN: Safeguarding LLM Multi-Agent Collaborations with Temporal Graph Modeling (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2505.19234)

---

## Contributing
Contributions are welcome! If you have a paper or resource to add, please feel free to open a pull request.

Please ensure your submission follows this format:
- `Paper Name (Conference / Journal, Year) 📄 [[paper]](link) 💻 [[code]](link)`

