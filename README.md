# Multi-Agent Deep Researcher (MADR)
## MCP-Enabled • Autonomous Research • Windows & Linux Compatible
https://cobusgreyling.medium.com/openai-deep-research-ai-agent-architecture-7ac52b5f6a01

## Overview

Multi-Agent Deep Researcher (MADR) is an advanced AI framework that uses multiple autonomous agents to perform deep research, long-context reasoning, task decomposition, document processing, and intelligent workflow execution.

Built on:

#### Multi-Agent architecture

#### MCP (Model Context Protocol)

#### FastAPI (Python backend)

#### Cross-platform support (Windows + Linux)

#### LLM-driven autonomous reasoning

MADR is designed for researchers, analysts, engineers, and AI developers who require an intelligent system capable of performing advanced multi-step research automatically.

### Key Features

### 🔎 Deep Research Mode
Multi-step research, validation, summarization, citations, and cross-checking.

### 🤖 Multi-Agent Collaboration
Planner Agent, Research Agent, Web-Search Agent, Summarizer Agent, Tool Agent.

### 🔌 MCP Integration
Supports tool calling, resource access, and multi-model interoperability.

### 🧩 Modular Agent Design
Add/remove agents effortlessly in agents.py.

### ⚡ FastAPI Backend
High-performance API for real-time research queries.

### 💻 Works on Windows & Linux
No OS-specific code—fully cross-platform.


# Architecture
                            User Query
                                ↓
                        API Server (FastAPI)
                                ↓
                      Task Router (agents.py)
                                ↓
           ┌─────────────── Multi-Agents ────────────────┐
           │                                             │
           │  Planner Agent → Research Agent → Validator │
           │     ↓                                       │
           │  Web Search Agent → Tool Agent → Summarizer │
           │                                             │
           └─────────────────────────────────────────────┘
                               ↓
             Final Research Report (JSON / Text / Markdown)
