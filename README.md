<div align="center">

# Awesome Local AI

**A curated list of local-first AI tools, frameworks, and self-hosted solutions.**

Your data stays on your hardware.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

</div>

---

## Contents

- [Inference Engines](#inference-engines)
- [Models](#models)
- [RAG & Knowledge](#rag--knowledge)
- [AI Agents & Frameworks](#ai-agents--frameworks)
- [MCP Ecosystem](#mcp-ecosystem)
- [Vector Databases](#vector-databases)
- [UI & Interfaces](#ui--interfaces)
- [Voice & Speech](#voice--speech)
- [Image & Vision](#image--vision)
- [Hardware](#hardware)
- [Deployment & Orchestration](#deployment--orchestration)
- [Privacy & Security](#privacy--security)

---

## Inference Engines

_Run LLMs locally on your own hardware._

| Tool | Description | Language |
|------|-------------|----------|
| [ollama](https://github.com/ollama/ollama) | Run LLMs locally with a simple API | Go |
| [llama.cpp](https://github.com/ggerganov/llama.cpp) | LLM inference in C/C++ | C++ |
| [vLLM](https://github.com/vllm-project/vllm) | High-throughput LLM serving | Python |
| [LocalAI](https://github.com/mudler/LocalAI) | OpenAI-compatible local API | Go |
| [LM Studio](https://lmstudio.ai/) | Desktop app for running local LLMs | Electron |

## Models

_Open-weight models you can run locally._

| Model | Parameters | Best for |
|-------|-----------|----------|
| [Llama 3](https://github.com/meta-llama/llama3) | 8B–70B | General purpose |
| [Mistral](https://mistral.ai/) | 7B–8x22B | Efficiency |
| [Qwen 2.5](https://github.com/QwenLM/Qwen2.5) | 0.5B–72B | Multilingual |
| [Phi-3](https://github.com/microsoft/Phi-3CookBook) | 3.8B–14B | Small & fast |
| [DeepSeek Coder](https://github.com/deepseek-ai/DeepSeek-Coder) | 1.3B–33B | Code generation |

## RAG & Knowledge

_Retrieval-Augmented Generation — connect AI to your documents._

| Tool | Description |
|------|-------------|
| [LangChain](https://github.com/langchain-ai/langchain) | Framework for LLM apps with retrieval |
| [LlamaIndex](https://github.com/run-llama/llama_index) | Data framework for LLM applications |
| [Haystack](https://github.com/deepset-ai/haystack) | End-to-end NLP/RAG framework |
| [RAGFlow](https://github.com/infiniflow/ragflow) | RAG engine with deep document understanding |
| [Anything LLM](https://github.com/Mintplex-Labs/anything-llm) | All-in-one desktop RAG app |

## AI Agents & Frameworks

_Build autonomous AI agents that run locally._

| Tool | Description |
|------|-------------|
| [CrewAI](https://github.com/crewAIInc/crewAI) | Multi-agent orchestration framework |
| [AutoGen](https://github.com/microsoft/autogen) | Multi-agent conversation framework |
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code) | Agentic coding in the terminal |
| [Hivekeep](https://github.com/MarlBurroW/hivekeep) | Self-hosted team of specialized AI agents with persistent memory and a web UI, in a single Bun + SQLite container |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | Open-source AI software developer |

## MCP Ecosystem

_Model Context Protocol — connect AI to tools and data._

| Tool | Description |
|------|-------------|
| [MCP Specification](https://modelcontextprotocol.io/) | The protocol specification |
| [MCP Servers](https://github.com/modelcontextprotocol/servers) | Reference server implementations |
| [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) | Build MCP servers in TypeScript |
| [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) | Build MCP servers in Python |

## Vector Databases

_Store and search embeddings locally._

| Tool | Description | Written in |
|------|-------------|-----------|
| [ChromaDB](https://github.com/chroma-core/chroma) | Open-source embedding database | Python |
| [Qdrant](https://github.com/qdrant/qdrant) | High-performance vector search | Rust |
| [Milvus](https://github.com/milvus-io/milvus) | Scalable vector database | Go |
| [Weaviate](https://github.com/weaviate/weaviate) | Vector search engine | Go |
| [LanceDB](https://github.com/lancedb/lancedb) | Serverless vector database | Rust |

## UI & Interfaces

_Chat UIs and dashboards for local AI._

| Tool | Description |
|------|-------------|
| [Open WebUI](https://github.com/open-webui/open-webui) | ChatGPT-style UI for local LLMs |
| [LibreChat](https://github.com/danny-avila/LibreChat) | Multi-provider chat interface |
| [Text Generation WebUI](https://github.com/oobabooga/text-generation-webui) | Gradio-based LLM interface |
| [Jan](https://github.com/janhq/jan) | Offline-first desktop AI assistant |

## Voice & Speech

_Local speech recognition and synthesis._

| Tool | Description |
|------|-------------|
| [Whisper](https://github.com/openai/whisper) | Speech-to-text by OpenAI |
| [Whisper.cpp](https://github.com/ggerganov/whisper.cpp) | C++ port of Whisper |
| [Piper](https://github.com/rhasspy/piper) | Fast local text-to-speech |
| [Coqui TTS](https://github.com/coqui-ai/TTS) | Deep learning TTS toolkit |

## Image & Vision

_Local image generation and understanding._

| Tool | Description |
|------|-------------|
| [Stable Diffusion WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) | Image generation UI |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | Node-based diffusion workflow |
| [Fooocus](https://github.com/lllyasviel/Fooocus) | Simple Stable Diffusion interface |

## Hardware

_Recommended hardware for running local AI._

| Device | Use case | Price range |
|--------|----------|-------------|
| NVIDIA RTX 4090 | Heavy inference, fine-tuning | $1,500+ |
| NVIDIA RTX 4060 Ti 16GB | Good balance for 7B–13B models | $400–500 |
| Apple M-series Mac | Unified memory, runs surprisingly well | $1,000+ |
| Intel NUC / Mini PC | Lightweight inference, MCP servers | $200–500 |
| Raspberry Pi 5 | Edge AI, small models | $80–100 |

## Deployment & Orchestration

_Run and manage local AI infrastructure._

| Tool | Description |
|------|-------------|
| [Docker](https://www.docker.com/) | Container runtime |
| [Proxmox](https://www.proxmox.com/) | Virtualization platform |
| [Portainer](https://www.portainer.io/) | Container management UI |
| [Traefik](https://traefik.io/) | Reverse proxy & load balancer |

## Privacy & Security

_Keep your data safe while using AI._

| Tool | Description |
|------|-------------|
| [WireGuard](https://www.wireguard.com/) | Fast, modern VPN |
| [Tailscale](https://tailscale.com/) | Zero-config mesh VPN |
| [CrowdSec](https://www.crowdsec.net/) | Collaborative security engine |

---

## Contributing

Know a great local-first AI tool? Open a PR! Please:
- Verify the tool actually runs locally / self-hosted
- Include a brief, accurate description
- Link to the official repo or website
- Keep entries alphabetically sorted within sections

## Why Local-First?

- **Privacy** — Your data never leaves your hardware
- **Cost** — No per-token API fees
- **Speed** — No network latency
- **Control** — Choose your models, tune your parameters
- **Offline** — Works without internet

---

<div align="center">

Curated by [LunoLabs](https://lunolabs.ch) — building local-first AI infrastructure for makers and companies.

</div>
