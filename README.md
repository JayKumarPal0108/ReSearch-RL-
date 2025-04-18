# ReSearch Project: Integrating Search and Reasoning with Reinforcement Learning

## 📘 Paper Reference
- **Title**: [ReSearch: Integrating Search and Reasoning with Reinforcement Learning for Large Language Models](https://arxiv.org/abs/2503.19470)
- **Authors**: Baichuan Inc., University of Edinburgh, Zhejiang University
- **Summary**: This paper introduces the ReSearch framework, which integrates external search operations into multi-step reasoning within large language models using reinforcement learning. It uses a novel approach called Group Relative Policy Optimization (GRPO) to decide *when* and *how* to search during reasoning.

## 📦 Official Repository
- **GitHub**: [Agent-RL/ReSearch](https://github.com/Agent-RL/ReSearch)
- The repo provides scripts, training pipelines, retriever serving, GRPO implementation, and pretrained model examples for ReSearch.

## 🧠 Objective
This project aims to:
1. Understand and summarize the ReSearch framework and its contributions.
2. Analyze the official GitHub repository and reproduce baseline experiments.
3. Implement the ReSearch framework with hands-on code.
4. Present key insights, findings, and potential future applications.

## 🔧 Implementation Highlights
- ✅ Reproduce baseline experiments from the paper
- ✅ Understand and apply GRPO in reinforcement learning
- ✅ Evaluate the model’s ability to reason and search interactively
- ✅ Build a working training loop and deploy retrieval interface

## 📊 Deliverables
- [x] **Working Implementation**
  - Core modules cloned and executed
  - Environment setup (Python, PyTorch, FlashRAG, FastAPI)
  - PPO training using GRPO algorithm

- [x] **Technical Summary Report**
  - Overview of reinforcement learning setup
  - GRPO explained: group-based advantage estimation without a critic
  - Evaluation metrics and experiment results

- [x] **Presentation Slides**
  - Motivation, design overview, and experimental insights
  - Challenges faced and technical decisions made
  - Reflections and model behavior observations

- [x] **Discussion Points**
  - **RAG vs. SFT vs. ReSearch**
    - RAG: retrieval-augmented but shallow reasoning
    - SFT: requires labeled reasoning steps
    - ReSearch: label-free, learns via trial and error with RL
  - **Future Integration**
    - Extend to tool use (e.g., calculators, code execution)
    - Real-time retrieval APIs
    - Reflection-aware LLM agents

## 🧪 Example Benchmarks
- HotpotQA
- MuSiQue
- 2WikiMultiHopQA
- Bamboogle

## 📂 Folder Structure Suggestion
```
ReSearch-Project/
├── notebooks/
│   ├── 1_environment_setup.ipynb
│   ├── 2_baseline_experiments.ipynb
│   ├── 3_grpo_exploration.ipynb
│   └── 4_evaluation.ipynb
├── scripts/
├── src/
│   ├── verl/        # GRPO module
│   └── flashrag/    # Retriever service
├── data/
├── presentation/   # Slides & discussion docs
└── README.md
```

## 🤝 Contributors
- [Your Name]
- [Group Members / Collaborators]

## 📌 License
This project is inspired by the official ReSearch repository under MIT License.

---
Feel free to fork, adapt, and build upon this framework for further research!
