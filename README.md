# 🤖 Awesome AI Agents

A curated list of AI agent frameworks, tools, platforms, and resources for building autonomous AI agents.

> Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a PR.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Contents

- [Agent Frameworks](#agent-frameworks)
  - [Multi-Framework Platforms](#multi-framework-platforms)
  - [Python Frameworks](#python-frameworks)
  - [TypeScript/JavaScript Frameworks](#typescriptjavascript-frameworks)
- [Agent Orchestration](#agent-orchestration)
  - [Multi-Agent Systems](#multi-agent-systems)
  - [Workflow & Pipeline Tools](#workflow--pipeline-tools)
- [Agent Infrastructure](#agent-infrastructure)
  - [Guardrails & Safety](#guardrails--safety)
  - [Monitoring & Observability](#monitoring--observability)
  - [Sandboxing & Isolation](#sandboxing--isolation)
  - [Memory & Context](#memory--context)
- [Agent Deployment](#agent-deployment)
  - [Hosting & Serving](#hosting--serving)
  - [Scaffolding & CLI Tools](#scaffolding--cli-tools)
- [Tool & Function Calling](#tool--function-calling)
  - [Tool Frameworks](#tool-frameworks)
  - [MCP Servers](#mcp-servers)
- [RAG & Knowledge](#rag--knowledge)
- [Coding Agents](#coding-agents)
  - [Terminal Agents](#terminal-agents)
  - [IDE Agents](#ide-agents)
- [General Purpose Agents](#general-purpose-agents)
- [Vertical Agents](#vertical-agents)
  - [Research & Analysis](#research--analysis)
  - [Customer Support](#customer-support)
  - [Data & Analytics](#data--analytics)
  - [DevOps & Infrastructure](#devops--infrastructure)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
- [Learning Resources](#learning-resources)
  - [Courses & Tutorials](#courses--tutorials)
  - [Books & Papers](#books--papers)
  - [Communities](#communities)

---

## Agent Frameworks

### Multi-Framework Platforms

Platforms that support multiple agent frameworks through a unified interface:

- [AgentVoy](https://github.com/agentvoy/agentvoy) — Universal AI agent platform. Scaffold, configure, guard, and deploy agents across 7 frameworks (OpenAI, Anthropic, CrewAI, LangGraph, Google ADK, LlamaIndex, AutoGen) with built-in guardrails, DevTools dashboard, and one-command deployment. ([Website](https://agentvoy.com))
- [LiteLLM](https://github.com/BerriAI/litellm) — Unified API proxy for 100+ LLM providers. Call OpenAI, Anthropic, Gemini, and more using the same interface with load balancing and spend tracking.
- [AI Gateway](https://github.com/Portkey-ai/gateway) — Unified API gateway for 200+ LLMs with automatic retries, caching, rate limiting, and request routing.

### Python Frameworks

- [LangChain](https://github.com/langchain-ai/langchain) — Framework for developing applications powered by LLMs with chains, agents, and retrieval-augmented generation.
- [LangGraph](https://github.com/langchain-ai/langgraph) — Library for building stateful, multi-actor agent applications as graphs with cycles, controllability, and persistence.
- [CrewAI](https://github.com/crewAIInc/crewAI) — Framework for orchestrating role-playing autonomous AI agents that work together to tackle complex tasks.
- [AutoGen](https://github.com/microsoft/autogen) — Multi-agent conversation framework from Microsoft Research for building LLM workflows with customizable and conversable agents.
- [Google ADK](https://github.com/google/adk-python) — Google's Agent Development Kit for building AI agents with Gemini models, tool use, and multi-agent orchestration.
- [LlamaIndex](https://github.com/run-llama/llama_index) — Data framework for LLM applications with data connectors, indexes, and query engines for building agents over your data.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) — OpenAI's official SDK for building multi-agent workflows with handoffs, guardrails, and tracing.
- [Anthropic SDK](https://github.com/anthropics/anthropic-sdk-python) — Official Python SDK for Claude with tool use, streaming, and vision support.
- [Haystack](https://github.com/deepset-ai/haystack) — End-to-end NLP framework for building production-ready pipelines for search, QA, and conversational AI agents.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) — Microsoft's SDK for integrating LLMs into apps with plugins, planners, and memory.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) — Agent framework built on Pydantic for type-safe AI agent development with dependency injection and structured outputs.
- [Marvin](https://github.com/prefecthq/marvin) — Lightweight AI engineering toolkit for building natural language interfaces with OpenAI function calling.
- [Instructor](https://github.com/jxnl/instructor) — Library for structured LLM outputs using Pydantic models with retry logic and validation.
- [DSPy](https://github.com/stanfordnlp/dspy) — Framework for programming LLMs as optimizable modules instead of prompting.
- [Smolagents](https://github.com/huggingface/smolagents) — Hugging Face's lightweight library for building agents with code-based actions and tool calling.
- [Agency Swarm](https://github.com/VRSEN/agency-swarm) — Agent orchestration framework focused on creating collaborative AI agent swarms with customizable roles.
- [Phidata](https://github.com/phidatahq/phidata) — Toolkit for building AI assistants with memory, knowledge, and tools using function calling.
- [Atomic Agents](https://github.com/BrainBlend-AI/atomic-agents) — Building AI agents with atomic, composable components based on Instructor.
- [Agno](https://github.com/agno-agi/agno) — Lightweight library for building multi-modal agents with memory, knowledge, tools, and reasoning.

### TypeScript/JavaScript Frameworks

- [Vercel AI SDK](https://github.com/vercel/ai) — TypeScript toolkit for building AI-powered applications with React, Next.js, Vue, Svelte, and Node.js.
- [Mastra](https://github.com/mastra-ai/mastra) — TypeScript agent framework with workflows, RAG, integrations, and syncs for building AI applications.
- [Bee Agent Framework](https://github.com/i-am-bee/bee-agent-framework) — Open source framework for building, deploying, and serving AI agents in TypeScript.
- [GenKit](https://github.com/firebase/genkit) — Google's framework for building AI-powered apps and agents in TypeScript and Go.

---

## Agent Orchestration

### Multi-Agent Systems

- [CrewAI](https://github.com/crewAIInc/crewAI) — Role-based multi-agent orchestration with sequential and parallel task execution.
- [AutoGen](https://github.com/microsoft/autogen) — Multi-agent conversations with customizable agent roles and group chat patterns.
- [LangGraph](https://github.com/langchain-ai/langgraph) — Graph-based multi-agent workflows with cycles, state management, and human-in-the-loop.
- [Swarm](https://github.com/openai/swarm) — OpenAI's experimental framework for lightweight multi-agent orchestration with handoffs and routines.
- [MetaGPT](https://github.com/geekan/MetaGPT) — Multi-agent framework that assigns different roles (PM, architect, engineer) to GPTs for collaborative software development.
- [ChatDev](https://github.com/OpenBMB/ChatDev) — Virtual software company powered by multiple AI agents playing different roles in the software development lifecycle.
- [CAMEL](https://github.com/camel-ai/camel) — Framework for studying cooperative behaviors of multi-agent systems with role-playing.
- [AgentVerse](https://github.com/OpenBMB/AgentVerse) — Platform for assembling multiple agents to collaboratively accomplish tasks.

### Workflow & Pipeline Tools

- [Prefect](https://github.com/PrefectHQ/prefect) — Workflow orchestration for data pipelines with a Python-based DAG framework.
- [Temporal](https://github.com/temporalio/temporal) — Durable execution platform for running reliable, long-running agent workflows.
- [Inngest](https://github.com/inngest/inngest) — Event-driven workflow engine for building reliable AI pipelines with retries and step functions.
- [Airflow](https://github.com/apache/airflow) — Platform for programmatically authoring, scheduling, and monitoring workflows.

---

## Agent Infrastructure

### Guardrails & Safety

- [Guardrails AI](https://github.com/guardrails-ai/guardrails) — Framework for adding structural, type, and quality assurance to LLM outputs with validators.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) — NVIDIA's toolkit for adding programmable guardrails to LLM-based conversational systems.
- [LLM Guard](https://github.com/protectai/llm-guard) — Security toolkit for LLM interactions with input/output scanners for prompt injection, PII, and toxicity.
- [Rebuff](https://github.com/protectai/rebuff) — Self-hardening prompt injection detector with multi-layered defense.
- [Lakera Guard](https://www.lakera.ai/) — API for protecting AI applications against prompt injections, data leakage, and harmful content.

### Monitoring & Observability

- [LangSmith](https://smith.langchain.com/) — Platform for debugging, testing, evaluating, and monitoring LLM applications and agents.
- [LangFuse](https://github.com/langfuse/langfuse) — Open source LLM engineering platform with traces, evals, prompt management, and metrics.
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) — Open source observability for LLM applications with tracing, evaluation, and dataset management.
- [Helicone](https://github.com/Helicone/helicone) — Open source LLM observability platform with logging, caching, rate limiting, and analytics.
- [Braintrust](https://www.braintrust.dev/) — Platform for evaluating, monitoring, and improving AI applications with logging and scoring.
- [Weave](https://github.com/wandb/weave) — Weights & Biases toolkit for tracking, evaluating, and improving LLM applications.

### Sandboxing & Isolation

- [E2B](https://github.com/e2b-dev/E2B) — Cloud sandboxes for AI agents with code execution, file system, and process management.
- [Daytona](https://github.com/daytonaio/daytona) — Development environment management platform with secure sandboxes for AI agents.
- [Modal](https://modal.com/) — Serverless cloud for running AI workloads with GPU support and container isolation.
- [Fly.io Machines](https://fly.io/docs/machines/) — Micro VMs for running isolated agent workloads with fast boot times.

### Memory & Context

- [Mem0](https://github.com/mem0ai/mem0) — Self-improving memory layer for LLM applications with personalized AI experiences.
- [Letta](https://github.com/letta-ai/letta) — Framework for building stateful AI agents with long-term memory and self-editing capabilities.
- [Zep](https://github.com/getzep/zep) — Long-term memory for AI assistants with conversation history, summaries, and vector search.
- [Chroma](https://github.com/chroma-core/chroma) — Open source embedding database for building AI applications with memory and retrieval.

---

## Agent Deployment

### Hosting & Serving

- [BentoML](https://github.com/bentoml/BentoML) — Framework for building, shipping, and scaling AI applications with model serving.
- [vLLM](https://github.com/vllm-project/vllm) — High-throughput LLM serving engine with PagedAttention for efficient memory management.
- [Ollama](https://github.com/ollama/ollama) — Run LLMs locally with a simple CLI and API for development and deployment.
- [LMStudio](https://lmstudio.ai/) — Desktop app for running local LLMs with an OpenAI-compatible API server.

### Scaffolding & CLI Tools

- [AgentVoy](https://github.com/agentvoy/agentvoy) — CLI that scaffolds agent projects across 7 frameworks with guardrails, DevTools, and deployment configs. `npx agentvoy create`.
- [Create LlamaIndex App](https://github.com/run-llama/create-llama) — CLI tool for creating LlamaIndex-powered applications with RAG templates.

---

## Tool & Function Calling

### Tool Frameworks

- [Composio](https://github.com/ComposioHQ/composio) — Platform for equipping AI agents with 250+ tools and integrations across SaaS apps.
- [Toolhouse](https://toolhouse.ai/) — Cloud infrastructure for running AI agent tools with sandboxed execution.
- [LangChain Tools](https://python.langchain.com/docs/integrations/tools/) — Extensive collection of pre-built tools for search, APIs, databases, and more.

### MCP Servers

- [Agent Payment Node](https://github.com/nuanu-ai/agent-payment-node) — Local CLI and stdio MCP payments on macOS; signing requires foreground owner approval.
- [Model Context Protocol](https://modelcontextprotocol.io/) — Anthropic's open protocol for connecting AI models to external data sources and tools.
- [MCP Servers](https://github.com/modelcontextprotocol/servers) — Official collection of MCP server implementations for various services.
- [Smithery](https://smithery.ai/) — Registry and platform for discovering and deploying MCP servers.

---

## RAG & Knowledge

- [LlamaIndex](https://github.com/run-llama/llama_index) — Data framework for ingesting, structuring, and querying private data with LLMs.
- [LangChain](https://github.com/langchain-ai/langchain) — RAG pipelines with document loaders, text splitters, embeddings, and vector stores.
- [Unstructured](https://github.com/Unstructured-IO/unstructured) — Open source toolkit for ingesting and pre-processing documents for RAG pipelines.
- [Docling](https://github.com/DS4SD/docling) — IBM's document processing library for converting PDFs, DOCX, and HTML to structured formats.
- [Embedchain](https://github.com/embedchain/embedchain) — Framework for creating RAG-powered chatbots over any data source.

---

## Coding Agents

### Terminal Agents

- [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview) — Anthropic's agentic coding tool that runs in the terminal with full codebase context.
- [Codex CLI](https://github.com/openai/codex-cli) — OpenAI's terminal agent for coding tasks with sandboxed code execution.
- [Aider](https://github.com/paul-gauthier/aider) — AI pair programming in the terminal that edits code in your local git repository.
- [OpenCode](https://github.com/opencode-ai/opencode) — Terminal-based AI coding agent with multi-provider support and MCP integration.
- [Goose](https://github.com/block/goose) — Open source AI developer agent from Block that operates on the command line.
- [Cody](https://github.com/sourcegraph/cody) — AI coding assistant from Sourcegraph with codebase-aware context.

### IDE Agents

- [Cursor](https://www.cursor.com/) — AI-native code editor forked from VS Code with chat, code generation, and multi-file editing.
- [Windsurf](https://windsurf.com/) — AI-powered IDE with Cascade for multi-file agentic coding workflows.
- [GitHub Copilot](https://github.com/features/copilot) — AI pair programmer with code completions, chat, and agent mode in VS Code.
- [Cline](https://github.com/cline/cline) — Autonomous AI coding agent for VS Code that creates/edits files and runs commands.
- [Continue](https://continue.dev/) — Open source AI code assistant extension for VS Code and JetBrains.
- [Augment Code](https://www.augmentcode.com/) — AI coding assistant with deep codebase understanding and team awareness.

---

## General Purpose Agents

- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) — Autonomous AI agent that chains LLM calls to achieve user-defined goals.
- [BabyAGI](https://github.com/yoheinakajima/babyagi) — AI task management system that creates, prioritizes, and executes tasks autonomously.
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) — Open source framework for building, managing, and running autonomous AI agents.
- [AgentGPT](https://agentgpt.reworkd.ai/) — Web-based platform for assembling, configuring, and deploying autonomous AI agents.
- [OpenDevin](https://github.com/OpenDevin/OpenDevin) — Open source platform for AI software developers as autonomous agents.
- [Devin](https://devin.ai/) — Autonomous AI software engineer by Cognition with full development environment access.
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) — Platform for AI-powered software development agents.
- [SWE-agent](https://github.com/princeton-nlp/SWE-agent) — Agent that resolves real GitHub issues by interacting with computer interfaces.

---

## Vertical Agents

### Research & Analysis

- [GPT Researcher](https://github.com/assafelovic/gpt-researcher) — Autonomous agent for comprehensive online research with report generation.
- [STORM](https://github.com/stanford-oval/storm) — Stanford's system for generating Wikipedia-like articles from scratch using LLMs.
- [Tavily](https://tavily.com/) — Search API optimized for AI agents and RAG applications.

### Customer Support

- [Intercom Fin](https://www.intercom.com/fin) — AI customer service agent powered by GPT-4 with knowledge base integration.
- [Forethought](https://forethought.ai/) — AI agent for customer support ticket resolution and workflow automation.

### Data & Analytics

- [Julius AI](https://julius.ai/) — AI data analyst that analyzes data, creates visualizations, and generates insights.
- [PandasAI](https://github.com/Sinaptik-AI/pandas-ai) — Python library that adds AI capabilities to pandas for conversational data analysis.
- [Vanna](https://github.com/vanna-ai/vanna) — AI SQL agent that generates accurate SQL queries from natural language.

### DevOps & Infrastructure

- [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt) — AI-powered Kubernetes troubleshooting with automated diagnostics.
- [Kubiya](https://kubiya.ai/) — AI agent for DevOps and platform engineering automation.

---

## Benchmarks & Evaluation

- [SWE-bench](https://github.com/princeton-nlp/SWE-bench) — Benchmark for evaluating AI agents on real-world software engineering tasks.
- [GAIA](https://huggingface.co/gaia-benchmark) — General AI assistants benchmark with real-world questions requiring multi-step reasoning.
- [AgentBench](https://github.com/THUDM/AgentBench) — Multi-dimensional benchmark for evaluating LLMs as agents.
- [HumanEval](https://github.com/openai/human-eval) — OpenAI's benchmark for evaluating code generation capabilities.
- [MMLU](https://github.com/hendrycks/test) — Massive Multitask Language Understanding benchmark for evaluating model knowledge.
- [Chatbot Arena](https://chat.lmsys.org/) — Crowdsourced platform for evaluating LLMs through human preference rankings.

---

## Learning Resources

### Courses & Tutorials

- [LangChain Academy](https://academy.langchain.com/) — Free courses on building with LangChain, LangGraph, and LangSmith.
- [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) — Free courses on LLMs, agents, and AI applications from Andrew Ng.
- [Hugging Face Agents Course](https://huggingface.co/learn/agents-course/unit0/introduction) — Free course on building AI agents with open source tools.

### Books & Papers

- [AI Agents in Production](https://www.manning.com/books/ai-agents-in-production) — Book on building production-ready AI agents.
- [ReAct: Synergizing Reasoning and Acting](https://arxiv.org/abs/2210.03629) — Foundational paper on the ReAct prompting paradigm for agents.
- [Toolformer](https://arxiv.org/abs/2302.04761) — Paper on language models teaching themselves to use tools.
- [Generative Agents](https://arxiv.org/abs/2304.03442) — Stanford/Google paper on interactive simulacra of human behavior.

### Communities

- [r/AI_Agents](https://www.reddit.com/r/AI_Agents/) — Reddit community for AI agent development.
- [LangChain Discord](https://discord.gg/langchain) — Community for LangChain developers.
- [AI Agent Hub Discord](https://discord.gg/ai-agents) — Community focused on AI agent builders.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a PR.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
