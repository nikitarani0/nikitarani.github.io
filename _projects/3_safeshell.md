---
layout: page
title: SafeShell
description: AI-Powered Transactional Linux Command Execution Framework
img: assets/img/safeshell_cover.png
importance: 3
category: work
github: https://github.com/nikitarani0/safeshell
---

Built for the CDAC Hackathon 2026. A framework that treats Linux command execution
as transactional — commands can be validated, sandboxed, and rolled back before
they cause damage, with an AI layer reasoning about command intent and risk.

**Stack:** Python, Bash AST parsing, SQLite, Ollama, Qwen3

**Key capabilities:**
- AST-level parsing of Bash commands to detect risky operations before execution
- Local LLM (Qwen3 via Ollama) for command-intent classification
- Transactional execution log in SQLite, enabling rollback and audit
