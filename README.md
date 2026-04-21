# Google Agent Development Kit — Working Through the Examples

A hands-on walkthrough of Google's **Agent Development Kit (ADK)** — 12 numbered examples that build from a single basic agent up to parallel, sequential, and stateful multi-agent systems.

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google_ADK-agents-4285F4?logo=google&logoColor=white)

## What's covered

Each folder is a self-contained, runnable agent example that introduces one new concept on top of the previous one:

| # | Example | Concept introduced |
|---|---|---|
| 1 | `1-basic-agent` | Minimum viable agent |
| 2 | `2-tool-agent` | Adding tools / function calling |
| 3 | `3-litellm-agent` | Running ADK with LiteLLM (non-Google models) |
| 4 | `4-structured-outputs` | Enforcing structured responses |
| 5 | `5-sessions-and-state` | Per-user conversation sessions |
| 6 | `6-persistent-storage` | Durable session storage |
| 7 | `7-multi-agent` | Multiple agents coordinating |
| 8 | `8-stateful-multi-agent` | Multi-agent with shared state |
| 9 | `9-callbacks` | Instrumenting with callbacks |
| 10 | `10-sequential-agent` | Sequential agent workflows |
| 11 | `11-parallel-agent` | Parallel agent fan-out |
| 12 | `12-loop-agent` | Agents that loop until done |

Plus `GEMINI_MODELS.md` with a reference of Gemini models you can point the agents at.

## Who this is for

- Engineers getting started with Google's ADK for the first time
- Folks already using LangChain/CrewAI who want to see how ADK's primitives compare
- Anyone evaluating whether ADK fits their agent architecture

## Quick start

```bash
git clone https://github.com/Hassan-Naeem-code/Google-Agent-Development-Kit.git
cd Google-Agent-Development-Kit

python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt

# Export your Google API key
export GOOGLE_API_KEY=...

# Run any example
cd 1-basic-agent
python main.py
```

## Repository layout

```
.
├── 1-basic-agent/
├── 2-tool-agent/
├── 3-litellm-agent/
├── 4-structured-outputs/
├── 5-sessions-and-state/
├── 6-persistent-storage/
├── 7-multi-agent/
├── 8-stateful-multi-agent/
├── 9-callbacks/
├── 10-sequential-agent/
├── 11-parallel-agent/
├── 12-loop-agent/
├── GEMINI_MODELS.md      # model reference
├── requirements.txt
└── README.md
```

## References

- Google ADK: https://github.com/google/adk-python
- Gemini API: https://ai.google.dev/

## License

MIT
