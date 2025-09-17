# agents-voice — 12th House AI
![Banner](../BRAND/banner.png)

## Overview
Voice agent for SMB workflows — integrates **Voiceflow**, **GPT-4o mini**, and **Zapier** to capture, process, and automate conversations.

## Features
- Voiceflow integration with AI logic
- Zapier hooks for automation
- Extendable with RAG modules

## Setup
1. Clone repo  
2. `cp .env.example .env` and fill values  
3. Install dependencies (if needed)  
4. See `docs/quickstart.md`  

## Structure
- `flows/` – Voiceflow exports (`placeholder.json` if empty)  
- `src/` – Core agent code (`voice.py`, `rag_stub.py`)  
- `docs/` – Quickstart & usage docs  

## Roadmap
- Next: Add RAG + MCP integration (future engineer task)
