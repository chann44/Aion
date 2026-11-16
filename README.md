# Aion

![Aion](./assets/aion.jpeg)

> Endless multi-agent system that builds software.

Aion is a self-organizing agent factory.  
Give it a goal. It plans, hires specialists, codes, tests, deploys, and iterates — continuously.

No beginning. No end.

![Python](https://img.shields.io/badge/Python-3.12+-blue) ![FastAPI](https://img.shields.io/badge/FastAPI-0.115+-green) ![LangGraph](https://img.shields.io/badge/LangGraph-agents-orange) ![Playwright](https://img.shields.io/badge/Playwright-computer--use-red)

`ai-agents` `multi-agent` `autonomous` `langgraph` `computer-use` `self-improving`

## Features

- Dynamic agent hiring
- Computer use (browser + desktop)
- Persistent memory
- Hard safety walls
- Live dashboard with real-time traces

## Stack

- Python + FastAPI
- LangGraph
- Playwright
- Postgres + pgvector
- Svelte kit dashboard
- Docker 

## Quick Start

```bash
uv sync
uv run uvicorn apps.api.main:app --reload
```

Open `http://localhost:3000`

## Structure

```
apps/          web + api
packages/      orchestrator, agents, memory, safety, computer-use
infra/         docker 
evals/         golden tasks
```

## License
MIT

