<div align="center">

<img src="https://raw.githubusercontent.com/protectyr-labs/.github/main/profile/assets/banner.svg" alt="Protectyr Labs: production-grade tools extracted from real systems" width="100%"/>

</div>

# Protectyr Labs

Open-source tools extracted from production systems. Each package solves a real problem encountered while building multi-agent systems, MCP servers, and AI-powered security products. Every one was battle-tested before being open-sourced. MIT licensed. Zero or minimal dependencies.

## MCP Servers and Templates

| Package | What it does | Lang |
|---------|-------------|------|
| [mcp-exec-team](https://github.com/protectyr-labs/mcp-exec-team) | On-demand panel of senior domain specialists for small teams. Ops, finance, security, product, legal. They collaborate, disagree, and stand their ground. | TS |
| [mcp-audit-wrapper](https://github.com/protectyr-labs/mcp-audit-wrapper) | Transparent audit logging for any MCP tool call. Wrap once, every call is logged without touching tool code. | TS |
| [mcp-starter](https://github.com/protectyr-labs/mcp-starter) | Production-grade MCP server template. Stdio transport, modular tools, graceful shutdown, audit logging. Start building tools on day one, not plumbing. | TS |

## LLM Infrastructure

| Package | What it does | Lang |
|---------|-------------|------|
| [token-budget](https://github.com/protectyr-labs/token-budget) | Smart token allocation for multi-layer prompts. Priority-based dropping when the context window fills up. | TS |
| [attack-validator](https://github.com/protectyr-labs/attack-validator) | MITRE ATT&CK technique ID validation. 3-tier hallucination detection so your security reports only cite real techniques. | TS |
| [vector-dedup](https://github.com/protectyr-labs/vector-dedup) | Semantic deduplication via embeddings. Feed in text with near-duplicates, get back clean groups. | TS |
| [file-preprocess](https://github.com/protectyr-labs/file-preprocess) | Any file format in, clean LLM-ready text out. PDF, DOCX, CSV, HTML. Smart truncation to fit context windows. | TS |
| [prompt-shield](https://github.com/protectyr-labs/prompt-shield) | Prompt injection detection. Regex-based, zero latency, zero cost. First-line defense before input reaches the model. | PY |

## Workflow and Orchestration

| Package | What it does | Lang |
|---------|-------------|------|
| [webhook-resume](https://github.com/protectyr-labs/webhook-resume) | Pause/resume for async workflows. Human-in-the-loop approval gates with timeout and multi-option routing. | TS |
| [funnel-state](https://github.com/protectyr-labs/funnel-state) | Typed state machine for customer lifecycle. Validated transitions, event sourcing, resubscription paths. | TS |
| [tier-state](https://github.com/protectyr-labs/tier-state) | Subscription tier resolution with trial state machine. 5-case trial logic, inline expiry, async and sync. | TS |
| [casl-consent](https://github.com/protectyr-labs/casl-consent) | CASL-compliant consent management. Express/implied consent, 2-year expiry, unsubscribe cascade. Avoid the $10M fine. | TS |

## Production Infrastructure

| Package | What it does | Lang |
|---------|-------------|------|
| [sse-lock](https://github.com/protectyr-labs/sse-lock) | SSE streaming with concurrency locking. For long-running LLM calls where you need progress and cannot have duplicates. | TS |
| [api-cache](https://github.com/protectyr-labs/api-cache) | Rate-limited API client with disk caching. Sliding window throttle, MD5-keyed cache. Stop hammering APIs. | PY |
| [streaming-json](https://github.com/protectyr-labs/streaming-json) | Process 100MB+ JSON without loading into memory. Streaming parser with progress tracking. | PY |
| [html2docx](https://github.com/protectyr-labs/html2docx) | HTML to Word with CSS variable resolution, bookmarks, formatting inheritance. Your styled reports come out as proper .docx. | PY |
| [halt-sentinel](https://github.com/protectyr-labs/halt-sentinel) | File-based circuit breaker for multi-agent systems. Any agent can halt all operations instantly. | PY |
| [atomic-jsonwrite](https://github.com/protectyr-labs/atomic-jsonwrite) | Crash-safe JSON persistence. fsync plus atomic replace. Your state file survives a power failure mid-write. | PY |
| [pairs-scanner](https://github.com/protectyr-labs/pairs-scanner) | Statistical arbitrage pairs scanner. Engle-Granger cointegration, Hurst exponent, half-life of mean reversion. | PY |
