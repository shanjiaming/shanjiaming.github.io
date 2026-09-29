---
# Display name
title: 单佳铭

# Name pronunciation
name_pronunciation: Jiaming Shan

# Full name for SEO
first_name: Jiaming
last_name: Shan

# Is this the primary user of the site?
superuser: true

# Role and affiliation
role: CS PhD Student at UCSB
organizations:
  - name: University of California, Santa Barbara
    url: https://www.ucsb.edu/

# Social links
profiles:
  - icon: at-symbol
    url: 'mailto:jiamingshan@ucsb.edu'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/shanjiaming
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/jiaming-shan-36249a298/
  - icon: Google_Scholar_logo
    url: https://scholar.google.com/citations?user=wDZa8XcAAAAJ&hl=en
---

I am a direct-entry Ph.D. student in Computer Science at the University of California, Santa Barbara (UCSB), advised by [Prof. Xifeng Yan](https://sites.cs.ucsb.edu/~xyan/). I am currently interning at Tencent Cloud WorkBuddy on post-training, reinforcement learning, and RSI, and I plan to master out with a master's degree in July 2027. My research focuses on **LLM efficiency, model architecture, speculative decoding, sparse and long-context attention, and autonomous agents**.

I aim to connect high-level agentic capabilities with low-level algorithmic innovations, treating model architecture and agent frameworks as complementary paths toward scalable, capable AI.

I have experience building agent systems. Previously, I earned my B.S. in Computer Science from Shanghai Jiao Tong University as a member of the ACM Honors Class.

---

# Publications & Manuscripts

## [Learning When Not to Attend Globally](/uploads/aha-manuscript.pdf)
**All-or-Here Attention (AHA)**; Xuan Luo\*, **Jiaming Shan**\*, Wesley Truong, Kailai Zhang, Hanzhe Zhang, Xifeng Yan<br>
*[Manuscript PDF](/uploads/aha-manuscript.pdf) (anonymous review copy); equal contribution*

Proposed a token-level adaptive attention mechanism whose binary router switches each attention head between global and sliding-window attention. On OLMo-2-1B with a 128-token window, **88.4% of token-head decisions chose local attention** with comparable aggregate performance across six benchmarks. AHA also improves DuoAttention as an orthogonal routing layer.

## [Proactive Agent Research Environment: Simulating Active Users to Evaluate Proactive Assistants](https://arxiv.org/abs/2604.00842)
Deepak Nathani, Cheng Zhang, Chang Huan, **Jiaming Shan**, Yinfei Yang, Alkesh Patel, Zhe Gan, William Yang Wang, Michael Saxon, Xin Eric Wang<br>
*arXiv preprint, 2026*

Built benchmark and environment abstractions for proactive and mobile agents, including finite-state-machine app modeling, goal inference, and multi-app orchestration evaluation.

## [Building Constrained Human-AI Cooperation: An Inclusive Embodied Social Intelligence Challenge](https://proceedings.neurips.cc/paper_files/paper/2024/hash/4eb8e997fc91086225b7484cf8eac341-Abstract-Datasets_and_Benchmarks_Track.html)
Weihua Du, Qiushi Lyu, **Jiaming Shan**, Zhenting Qi, Hongxin Zhang, Sunli Chen, Andi Peng, Tianmin Shu, Kwonjoon Lee, Behzad Dariush, Chuang Gan<br>
**NeurIPS 2024**, Datasets and Benchmarks Track; poster

Conceptualized and implemented physically constrained agents and helper bots in ThreeDWorld, using in-context learning to deploy language-based agents for human-assistance tasks and construct a new benchmark dataset.

## [Building Cooperative Embodied Agents Modularly with Language Models](https://openreview.net/forum?id=zGrM0f50s7s)
Hongxin Zhang\*, Weihua Du\*, **Jiaming Shan**, Qinhong Zhou, Yilun Du, Joshua B. Tenenbaum, Tianmin Shu, Chuang Gan<br>
**ICLR 2024**; poster; equal contribution

Co-developed a prompt-based state-abstraction framework for multi-agent cooperation, led the VirtualHome environment and heuristic-baseline implementation, and conducted user studies comparing LLM agents with planning baselines.

---

# Research Experience

## University of California, Santa Barbara
**Ph.D. Student in Computer Science**; advisor: Prof. Xifeng Yan; September 2024 - Present

- Co-first-authored All-or-Here Attention and contributed to real-world acceleration and inference-speedup code paths.
- Explored end-to-end fine-tuning for DFlash acceleration.
- Built benchmark and environment abstractions for PARE.

## Massachusetts Institute of Technology
**Summer Research, CSAIL**; advisor: Prof. Chuang Gan; August 2023 - June 2024

- Designed physically constrained agents and helper bots in the ThreeDWorld simulation environment.
- Deployed language-based agents for human-assistance tasks and benchmark generation.

## MIT / Shanghai Jiao Tong University
**Remote Research**; advisor: Prof. Chuang Gan; February 2023 - May 2023

- Co-developed a prompt-based state-abstraction framework for multi-agent cooperation.
- Led VirtualHome environment and heuristic-baseline implementation and conducted user studies.

---

# Internship Experience

## Tencent Cloud WorkBuddy
**Large Language Model Agent Research Intern**; September 2026 - Present

- Trained large language model agents from experience data and conducted research on RSI.

## RWKV
**Agent Intern**; March 2026 - June 2026

- Developed high-concurrency local document summarization and retrieval pipelines.
- Used RWKV to summarize tool outputs and extract key information, reducing downstream token consumption.
- Concurrently generated readable HTML views alongside the primary output.

---

# Agent Daily Use

- **Auto Research in Scientific Work.** Use auto-research workflows for question decomposition, reference search and synthesis, experiment planning, and reusable research notes; summarized practical lessons in [this article](https://zhuanlan.zhihu.com/p/2009629370684306095).
- **TA Grading Agent.** Converted the Gradescope grading interface into MCP tools and agent workflows for batch grading; dual-pass grading and human-verification queues reduce TA workload by roughly **70%**.
- **Thought-to-Blog Agent.** Built a pipeline that turns high-signal AI chat records into publishable blog drafts through privacy/value screening and staged working, final, and published versions.
- **Autonomous Wealth Research Agent.** Built a daily investing automation connected to moomoo and a local agent workforce, with portfolio-aware recommendations, supply-chain research, tax and cash-flow constraints, risk gates, and simulated trading.
- **OpenClaw-like Personal Agent Framework.** Developed and use a personal agent framework integrating memory, sleep and compaction, MCP tool routing, and long-running personal workflows.

---

# Education

## Shanghai Jiao Tong University
**B.S. in Computer Science**; ACM Honors Class; September 2020 - June 2024

- Elite Computer Science program for students selected from the top 5%.
- GPA in core courses: **3.98/4.3**, ranked **3/36**.
- 2023 National Scholarship.

## University of California, Santa Barbara
**Ph.D. Student in Computer Science**; advisor: Prof. Xifeng Yan; September 2024 - Present

---

# Honors & Awards

- 2023 National Scholarship Award
- Zhiyuan Honorary Scholarship, 2020-2023 (Top 2% at Shanghai Jiao Tong University)
- 2021 Interdisciplinary Contest in Modeling, Honorable Mention
- 2021 National Undergraduate Mathematical Contest in Modeling, Provincial Third Prize
- 2021 International Physics Competition for University Students, Silver Medal

---

# Technical Skills

- **AI / ML:** PyTorch, Hugging Face, Triton, FlashAttention, vLLM, Weights & Biases
- **AI-native workflow:** Codex, OpenClaw, Cursor, Claude Code, Tmux
- **Programming:** Python, C++, Lisp, Java
- **Developer tools:** Git, Docker, LaTeX
