# Awesome-Graph-augmented-LLM-Agent (GLA)
 [![Awesome](https://awesome.re/badge.svg)](https://github.com/RManLuo/Awesome-LLM-KG) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
  ![](https://img.shields.io/github/last-commit/Shiy-Li/Awesome-Graph4Agent-Systems?color=green) 
 ![](https://img.shields.io/github/stars/Shiy-Li/Awesome-Graph4Agent-Systems?color=yellow)
![](https://img.shields.io/github/forks/Shiy-Li/Awesome-Graph4Agent-Systems?color=lightblue) 

A curated list of awesome papers and resources on leveraging graph structures / algorithm to enhance LLM-based Agent Systems.

## 🗺️ Table of Contents

- [Graph-Augmented LLM Agent System Framework](#graph-augmented-llm-agent-system-framework)
  - [🧠 Graphs for Agent Planning](#🧠-graphs-for-agent-planning)
  - [💾 Graphs for Agent Memory Management](#💾-graphs-for-agent-memory-management)
  - [🛠️ Graphs for Tool Management](#🛠️-graphs-for-tool-management)
- [Graph-Augmented LLM Multi-Agent Systems](#graph-augmented-llm-multi-agent-systems)
  - [🕸️ Graphs for MAS Orchestration](#🕸️-graphs-for-mas-orchestration)
  - [⚡ Graph for MAS Efficiency](#⚡-graph-for-mas-efficiency)
  - [🛡️ Graphs for Trustworthy MAS](#🛡️-graphs-for-trustworthy-mas)

---

## Graph-Augmented LLM Agent System Framework

### 🧠 Graphs for Agent Planning

#### Plan as a Graph
- AFlow: Automating Agentic Workflow Generation (ICLR, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.10762) 💻 [[code]](https://github.com/FoundationAgents/AFlow)
- VFlow: Discovering Optimal Agentic Workflows for Verilog Generation (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2504.03723)
- AgentKit: Structured LLM Reasoning with Dynamic Graphs (CLM, 2024) 📄 [[paper]](https://arxiv.org/abs/2402.14034) 💻 [[code]](https://github.com/agentkit/agentkit)
- Plan-over-Graph: Towards Parallelable LLM Agent Schedule (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.14563) 💻 [[code]](https://github.com/zsq259/Plan-over-Graph)
- Benchmarking Agentic Workflow Generation (ICLR, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.07869) 💻 [[code]](https://github.com/zjunlp/WorfBench)

#### Sub-task Pool as a Graph
- Can Graph Learning Improve Planning in LLM-based Agents? (NeurIPS, 2024) 📄 [[paper]](https://arxiv.org/abs/2405.19119) 💻 [[code]](https://github.com/WxxShirley/GNN4TaskPlan)
- Hugginggpt: Solving ai tasks with chatgpt and its friends in hugging face (NeurIPS, 2023) [[paper]]()

#### Reasoning Thought as a Graph
- Chain-of-thought prompting elicits reasoning in large language models (NeurIPS, 2023) 📄 [[paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/9d5609613524ecf4f15af0f7b31abca4-Paper-Conference.pdf)
- Tree of Thoughts: Deliberate Problem Solving with Large Language Models (NeurIPS, 2023) 📄 [[paper]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/271db9922b8d1f4dd7aaef84ed5ac703-Abstract-Conference.html) 💻 [[code]](https://github.com/princeton-nlp/tree-of-thought-llm)
- RATT: A Thought Structure for Coherent and Correct LLM Reasoning (AAAI, 2025) 📄 [[paper]](https://arxiv.org/abs/2501.02474)
- Graph of Thought: Solving Elaborate Problems with Large Language Models (AAAI, 2024) 📄 [[paper]](https://arxiv.org/abs/2308.09687) 💻 [[code]](https://github.com/spcl/graph-of-thoughts)
- Thought Graph: Generating Thought Process for Biological Reasoning (WWW, 2024) 📄 [[paper]](https://arxiv.org/abs/2402.19480)
- Graph of Goal-Oriented Thoughts: Design and Implementation of LLM Agents (SOCIALIZE, 2025) 📄 [[paper]](https://arxiv.org/abs/2501.02474)


#### Environment as a Graph
- Graphormer-Guided Task Planning: Beyond Static Rules with LLM Safety Perception (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.06866) 💻 [[code]](https://github.com/hwj20/GGTP)
- LocAgent: Graph-Guided LLM Agents for Code Localization (ACL, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.09089) 💻 [[code]](https://github.com/gersteinlab/LocAgent)

### 💾 Graphs for Agent Memory Management

#### Graph-organized Interaction Memory
- A-MEM: Agentic Memory for LLM Agents (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.12110) 💻 [[code]](https://github.com/WujiangXu/AgenticMemory)
- AriGraph: Learning Knowledge Graph World Models with Episodic Memory for LLM Agents (arxiv, 2024) 📄 [[paper]](https://arxiv.org/abs/2407.04363) 💻 [[code]](https://github.com/AIRI-Institute/AriGraph)

#### Graph-organized Knowledge Memory
- Synergizing LLM Agents and Knowledge Graph for Socioeconomic Prediction in LBSN (arxiv, 2024) 📄 [[paper]](https://arxiv.org/abs/2411.00028)
- KG-Agent: An Efficient Autonomous Agent Framework for Complex Reasoning over Knowledge Graph (ACL, 2025) 📄 [[paper]](https://arxiv.org/abs/2406.14550)

### 🛠️ Graphs for Tool Management

#### Tool Graphs for Tool Selection
- ControlLLM: Augment Language Models with Tools by Searching on Graphs (ECCV, 2024) 📄 [[paper]](https://arxiv.org/abs/2403.00839) 💻 [[code]](https://github.com/OpenBMB/ControlLLM)
- SciToolAgent: A Knowledge Graph-Driven Scientific Agent for Multi-Tool Integration (preprint, 2025) 📄 [[paper]](https://doi.org/10.21203/rs.3.rs-5610718/v1) 💻 [[code]](https://github.com/HICAI-ZJU/SciToolAgent)
- ToolNet: Connecting large language models with massive tools via tool graph (arxiv, 2024) 📄 [[paper]](https://arxiv.org/abs/2403.00839)

#### Tool Graphs Improve Agent Tool-use Capability
- ToolFlow: Boosting LLM Tool-Calling Through Natural and Coherent Dialogue Synthesis (NAACL, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.18447)

---

## Graph-Augmented LLM Multi-Agent Systems

### 🕸️ Graphs for MAS Orchestration

#### Static MAS Topology
- AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation (ICLR 2024 workshop) 📄 [[paper]](https://openreview.net/pdf?id=BAakY1hNKS) 💻 [[code]](https://github.com/microsoft/autogen)
- Chateval: Towards better llm-based evaluators through multi-agent debate (ICLR, 2023) 📄 [[paper]](https://arxiv.org/pdf/2308.07201) 💻 [[code]](https://github.com/thunlp/ChatEval)
- Improving factuality and reasoning in language models through multiagent debate (ICML, 2024) 📄 [[paper]](https://openreview.net/pdf?id=zj7YuTE4t8) 💻 [[code]](https://github.com/composable-models/llm_multiagent_debate)
- GPTSwarm: Language Agents as Optimizable Graphs (ICML, 2024) 📄 [[paper]](https://arxiv.org/abs/2402.16823) 💻 [[code]](https://github.com/metauto-ai/gptswarm)
- Scaling Large Language Model-based Multi-Agent Collaboration (ICLR, 2025) 📄 [[paper]](https://arxiv.org/abs/2406.07155) 💻 [[code]](https://github.com/OpenBMB/ChatDev/tree/macnet)
- AFlow: Automating Agentic Workflow Generation (ICLR, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.10762) 💻 [[code]](https://github.com/FoundationAgents/AFlow)
- EvoFlow: Evolving Diverse Agentic Workflows On The Fly (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.07373)

#### Task-dynamic MAS Topology
- G-Designer: Architecting Multi-agent Communication Topologies via Graph Neural Networks (ICML, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.11782) 💻 [[code]](https://github.com/yanweiyue/GDesigner)
- Understanding the Information Propagation Effects of Communication Topologies in LLM-based Multi-Agent Systems (EMNLP, 2025) 📄 [[paper]](https://arxiv.org/abs/2501.02474) 💻 [[code]](https://github.com/se7esx/EIB/)
- Assemble Your Crew: Automatic Multi-agent Communication Topology Design via Autoregressive Graph Generation (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2507.18224) 💻 [[code]](https://github.com/Shiy-Li/ARG-Designer)
- GNNs as Predictors of Agentic Workflow Performances (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.11301) 💻 [[code]](https://github.com/youngsoul0731/Flora-Bench)
- Multi-agent Architecture Search via Agentic Supernet (ICML, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.04180) 💻 [[code]](https://github.com/bingreeky/MaAS)
- Multi-Agent Design: Optimizing Agents with Better Prompts and Topologies (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.02533)

#### Process-dynamic MAS Topology
- ReSo: A Reward-driven Self-organizing LLM-based Multi-Agent System for Reasoning Tasks (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.02390) 💻 [[code]](https://github.com/hengzzzhou/ReSo)
- Self-evolving Multi-agent Collaboration Networks for Software Development (ICLR, 2025) 📄 [[paper]](https://arxiv.org/abs/2501.02474)
- AnyMAC: Cascading Flexible Multi-Agent Collaboration via Next-Agent Prediction (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2506.17784)

### ⚡ Graph for MAS Efficiency

#### Edge Redundancy in MAS
- Cut the Crap: An Economical Communication Pipeline for LLM-based Multi-Agent Systems (ICLR, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.02506) 💻 [[code]](https://github.com/yanweiyue/AgentPrune)
- Improving Multi-Agent Debate with Sparse Communication Topology (Findings of EMNLP, 2024) 📄 [[paper]](https://arxiv.org/abs/2405.19119)
- Talk structurally, act hierarchically: A collaborative framework for llm multi-agent systems (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.11098) 💻 [[code]](https://github.com/sony/talkhier)

#### Node Redundancy in MAS
- AgentDropout: Dynamic Agent Elimination for Token-Efficient and High-Performance LLM-Based Multi-Agent Collaboration (ACL, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.18891) 💻 [[code]](https://github.com/wangzx1219/AgentDropout)

#### Layer Redundancy in MAS
- RMoA: Optimizing Mixture-of-Agents through Diversity Maximization and Residual Compensation (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2505.24442)
- Debate Only When Necessary: Adaptive Multiagent Collaboration for Efficient LLM Reasoning (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2504.05047)

### 🛡️ Graphs for Trustworthy MAS
- G-Safeguard: A Topology-Guided Security Lens and Treatment on LLM-based Multi-agent Systems (ACL, 2025) 📄 [[paper]](https://arxiv.org/abs/2502.11127) 💻 [[code]](https://github.com/wslong20/G-safeguard)
- NetSafe: Exploring the Topological Safety of Multi-agent Network (ACL, 2025) 📄 [[paper]](https://arxiv.org/abs/2410.15686) 💻 [[code]](https://anonymous.4open.science/r/NetSafe-B726/README.md)
- AgentSafe: Safeguarding Large Language Model-based Multi-agent Systems via Hierarchical Data Management (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2503.04392) 💻 [[code]](https://github.com/junyuanM/Agentsafe)
- Goal-Aware Identification and Rectification of Misinformation in Multi-Agent Systems (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2506.00509)
- FlowReasoner: Reinforcing Query-level Meta-agents (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2504.15257)
- Agent-SafetyBench: Evaluating the Safety of LLM Agents (arxiv, 2024) 📄 [[paper]](https://arxiv.org/abs/2412.14470)
- AgentAuditor: Human-Level Safety and Security Evaluation for LLM Agents (arxiv, 2025) 📄 [[paper]](https://arxiv.org/abs/2506.00641)

---

## Contributing
Contributions are welcome! If you have a paper or resource to add, please feel free to open a pull request.

Please ensure your submission follows this format:
- `Paper Name (Conference / Journal, Year) 📄 [[paper]](link) 💻 [[code]](link)`

---

## Citation

If you find this repository helpful for your work, please kindly cite:

```bibtex
@article{liu2025graph,
  title={Graph-Augmented Large Language Model Agents: Current Progress and Future Prospects},
  author={Liu, Yixin and Zhang, Guibin and Wang, Kun and Li, Shiyuan and Pan, Shirui},
  journal={arXiv preprint arXiv:2501.02474},
  year={2025}
}
```