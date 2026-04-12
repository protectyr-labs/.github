# Protectyr Labs

Open-source tools extracted from Protectyr's production cybersecurity platform.
Each package solves a real problem we encountered building multi-agent systems,
MCP servers, and AI-powered SaaS products.

## MCP & Multi-Agent

| Package | Description | Language |
|---------|------------|----------|
| [mcp-exec-team](https://github.com/protectyr-labs/mcp-exec-team) | Multi-persona debate engine as MCP server | TypeScript |
| [mcp-audit-wrapper](https://github.com/protectyr-labs/mcp-audit-wrapper) | Transparent audit logging HOF for MCP tool calls | TypeScript |

## LLM Infrastructure

| Package | Description | Language |
|---------|------------|----------|
| [token-budget](https://github.com/protectyr-labs/token-budget) | Smart token allocation for multi-layer LLM prompts | TypeScript |
| [attack-validator](https://github.com/protectyr-labs/attack-validator) | MITRE ATT&CK technique ID hallucination detection | TypeScript |
| [vector-dedup](https://github.com/protectyr-labs/vector-dedup) | Semantic deduplication using vector embeddings | TypeScript |
| [prompt-shield](https://github.com/protectyr-labs/prompt-shield) | Prompt injection detection for untrusted LLM inputs | Python |

## Production Infrastructure

| Package | Description | Language |
|---------|------------|----------|
| [sse-lock](https://github.com/protectyr-labs/sse-lock) | SSE streaming API routes with concurrency locking | TypeScript |
| [streaming-json](https://github.com/protectyr-labs/streaming-json) | Process 100MB+ JSON files without loading into memory | Python |
| [halt-sentinel](https://github.com/protectyr-labs/halt-sentinel) | File-based circuit breaker for multi-agent systems | Python |
| [atomic-jsonwrite](https://github.com/protectyr-labs/atomic-jsonwrite) | Crash-safe JSON persistence with fsync + atomic replace | Python |

## Origin

These tools were extracted from production systems processing real security
assessments, incident response cases, and multi-agent workflows. Each one
was battle-tested before being open-sourced.

MIT Licensed.
