# Hi

I'm pursuing an Sc.M. in Electrical and Computer Engineering at Brown University.

I build and evaluate tool-using agents that solve multi-step real-world tasks.

[LinkedIn](https://www.linkedin.com/in/sihan-long/)

## Featured Projects

### [ClassPort](https://github.com/DonSteven/ClassPort)

A self-hostable dashboard for courses, deadlines, and study materials. I built an OAuth-protected MCP integration so ChatGPT can read course PDFs and save follow-up tasks to the same dashboard. PostgreSQL tracks indexing jobs so interrupted work can be retried after a worker failure.

[Explore the repository →](https://github.com/DonSteven/ClassPort) · [Try the sample semester](https://lab4long.dev/app)

`MCP` · `OAuth` · `FastAPI` · `PostgreSQL` · `Celery` · `Redis`

### [ToolAgent-RL](https://github.com/DonSteven/ToolAgent-RL)

A post-training and evaluation workflow for tool-using agents on long, multi-turn tau2-bench Airline tasks. I distill successful teacher conversations into a 7B policy, collect online tool-use rollouts, and study sparse rewards and long-trajectory training through group-relative policy updates.

`Agentic RL` · `Teacher distillation` · `QLoRA` · `GRPO-style training`

[Explore the repository →](https://github.com/DonSteven/ToolAgent-RL) · [Results and ablations](https://github.com/DonSteven/ToolAgent-RL/blob/main/reports/results_and_ablations.md)

### [Memento Bot](https://github.com/DonSteven/memento-bot)

An AI assistant that remembers useful context across conversations and retrieves evidence from a persistent knowledge store. My extensions to nanobot focus on choosing what to remember, checking whether retrieved evidence addresses a question, and keeping context within budget.

`Long-term memory` · `Hybrid retrieval` · `Evidence-aware RAG` · `Context management`

[Explore the repository →](https://github.com/DonSteven/memento-bot) · [What I added](https://github.com/DonSteven/memento-bot#what-i-changed) · [Dashboard playback](https://github.com/DonSteven/memento-bot#demo)

## What I'm working on

- **Agents:** Connecting agents to application data and actions through authenticated tools, with memory, retrieval, and execution traces to support and inspect their work.
- **Backend Engineering:** Building asynchronous Python services with persistent state, reliable background processing, and recovery from interrupted tasks.
- **Post-training & Evaluation:** Combining teacher distillation and reinforcement learning for multi-turn tool use, then using task-level evaluation and failure analysis to guide training.
