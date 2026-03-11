# kryptomrx

*Infrastructure · Systems Exploration · Automation*

I spend my time taking systems apart, figuring out how they work, and attempting to rebuild them. I am currently learning deep infrastructure, secure routing, and how to optimize data flows.

## What I'm Learning & Building

*   **Infrastructure:** Exploring isolated, self-hosted environments (Kubernetes, Istio, custom Matrix Synapse setups).
*   **Architecture:** Experimenting with zero-trust network models and alternative communication protocols.
*   **Workflow Optimization:** Maintaining [TONL-MCP Bridge](https://github.com/kryptomrx/tonl-mcp-bridge) to understand and improve token efficiency in LLM APIs.

## Current Toolkit

*These are the tools I'm actively using and learning:*

*   **Ops & Routing:** Linux, Docker, K8s, Istio
*   **Scripting:** Python, TypeScript, Bash
*   **AI Integration:** MCP Servers, API orchestration, RAG architectures
*   **Documentation & Web:** LaTeX, Svelte/Astro

## Highlighted Experiment

### [TONL-MCP Bridge](https://github.com/kryptomrx/tonl-mcp-bridge)
[![npm](https://img.shields.io/npm/v/tonl-mcp-bridge)](https://www.npmjs.com/package/tonl-mcp-bridge)
[![Tests](https://img.shields.io/badge/tests-45%20passing-brightgreen)](https://github.com/kryptomrx/tonl-mcp-bridge)

A tool I built to learn about and reduce token overhead. It converts JSON/YAML into high-density TONL structures to save context window space in automated pipelines.
```bash
npm install -g tonl-mcp-bridge
```
