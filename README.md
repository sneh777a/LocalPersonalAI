# LocalPersonalAI

Personal AI, On Personal Devices.

Local-first personal AI agent framework. Runs on your hardware by default. Cloud optional.

Inspired by OpenJarvis.

## Quick Start

```bash
pip install -e .
python -m localai chat
```

## Structure

- `src/localai/` - Core framework
- `agents/` - Agent implementations
- `engines/` - Local model backends (Ollama, llama.cpp)
- `tools/` - Tool integrations

## Goals

- Shared primitives for on-device agents
- Efficiency metrics (energy, latency, cost) first-class
- Local learning from traces
