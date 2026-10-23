# MCP Reading Group — Reading List

Papers for our lab's paper-reading session on the **Model Context Protocol (MCP)**.
Each entry lists the paper's exact title, its authors, its year, and one line on why it is worth reading.

---

## 1. Model Context Protocol (MCP): Landscape, Security Threats, and Future Research Directions

- **Authors:** Xinyi Hou, Yanjie Zhao, Shenao Wang, Haoyu Wang
- **Year:** 2025
- **Why it's worth reading:** The first systematic academic study of the whole MCP ecosystem — it defines the full MCP server lifecycle, builds a 16-scenario threat taxonomy across four attacker types, and maps concrete security safeguards to each lifecycle phase, making it the best single entry point for understanding both how MCP works and where it breaks.

## 2. Model Context Protocol (MCP) at First Glance: Studying the Security and Maintainability of MCP Servers

- **Authors:** Mohammed Mehedi Hasan, Hao Li, Emad Fallahzadeh, Gopi Krishnan Rajbahadur, Bram Adams, Ahmed E. Hassan
- **Year:** 2025
- **Why it's worth reading:** A large-scale empirical study of 1,899 real-world MCP servers (583 with >10 stars) that measures code quality, maintainability, and MCP-specific risks such as tool poisoning — the ground-truth view of what the ecosystem actually looks like in practice rather than on paper.

## 3. A survey of agent interoperability protocols: Model Context Protocol (MCP), Agent Communication Protocol (ACP), Agent-to-Agent Protocol (A2A), and Agent Network Protocol (ANP)

- **Authors:** Abul Ehtesham, Aditi Singh, Gaurav Kumar Gupta, Saket Kumar
- **Year:** 2025
- **Why it's worth reading:** It situates MCP in the wider landscape of agent interoperability standards by comparing it against ACP, A2A, and ANP across interaction modes, discovery mechanisms, and security models, and proposes a phased adoption roadmap from tool access to decentralized agent marketplaces.

## 4. MCP-Universe: Benchmarking Large Language Models with Real-World Model Context Protocol Servers

- **Authors:** Ziyang Luo, Zhiqi Shen, Wenzhuo Yang, Zirui Zhao, Prathyusha Jwalapuram, Amrita Saha, Doyen Sahoo, Silvio Savarese, Caiming Xiong, Junnan Li
- **Year:** 2025
- **Why it's worth reading:** The first comprehensive benchmark for evaluating LLMs on real production MCP servers (11 servers, 133 tools, 231 tasks across six domains) with execution-based rather than LLM-as-a-judge evaluation — showing even top models score below 44% success and exposing the long-context and unknown-tools bottlenecks.

---

*Suggested session order: paper 1 (landscape and security) → paper 2 (empirical study of real servers) → paper 3 (MCP among interoperability protocols) → paper 4 (how well do models actually use MCP).*
