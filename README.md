## Hey, I'm Haris

I'm a backend engineer based in Islamabad.

Most of my work is on data-heavy systems. We crawl regulatory documents from stock exchanges and pull structured fee data out of them with LLM pipelines. The hard part is knowing when the output is right, so a lot of what I build is evaluation and scoring.

That work is in private company repos. What is public here is smaller: one VS Code extension and a couple of upstream contributions.

---

### Open source

- **[paygraph](https://github.com/paygraph-ai/paygraph)**: spend governance for AI agents. I added pause and resume for human approval in LangGraph agents, so a spend that needs approval pauses the graph until someone decides in Slack ([#33](https://github.com/paygraph-ai/paygraph/pull/33)). I also proposed the two-node version, which the maintainers built and now recommend.
- **[agent_cli](https://github.com/Sami606713/agent_cli)**: a CLI that scaffolds and runs LangChain agents. I made the frontend and agent ports configurable in `agent.yaml`, and old configs migrate on load ([#9](https://github.com/Sami606713/agent_cli/pull/9), merged through [#11](https://github.com/Sami606713/agent_cli/pull/11)).

---

### Projects

- **[claude-code-commits](https://marketplace.visualstudio.com/items?itemName=HarisKhan1596.claude-code-commits)**: a VS Code extension that writes commit messages with the Claude CLI. Over 300 installs on the Marketplace. The source is in [claude-code-commit](https://github.com/haris-khan1596/claude-code-commit).

---

### Stack

**Backend**: Python · FastAPI · Celery · Scrapy · Node.js  
**AI / LLM**: LangGraph · RAG · hybrid BM25 + vector search · DeepEval · Langfuse · MCP  
**Data**: PostgreSQL · Redis · Elasticsearch · Neo4j · MongoDB  
**Infra**: AWS (ECS Fargate · SQS · Lambda · S3) · Pulumi · Docker · GitHub Actions · Grafana Loki  

---

[harris.khan.1596@gmail.com](mailto:harris.khan.1596@gmail.com) · [LinkedIn](https://www.linkedin.com/in/haris-khan-1596-harry/)
