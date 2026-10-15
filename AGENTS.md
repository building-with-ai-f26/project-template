# AGENTS.md — Coding Agent Operating Manual

> Coding agents (Claude Code, Codex, OpenCode, Pi) read this file automatically. Keep it updated as your project evolves so your agent knows your stack, commands, and ground rules.

## 1. Project Overview
- **What this repo builds:** [1–2 sentence summary]
- **Primary user & core workflow:** [See `Intent.md` and `Plan.md`]
- **Tech stack:** [e.g., Python 3.12 / FastAPI / Next.js / SQLite / OpenRouter API]

## 2. Commands
- **Install dependencies:** `[e.g., npm install / uv sync]`
- **Run locally:** `[e.g., npm run dev]`
- **Run deterministic tests:** `[e.g., pytest / npm test]`
- **Run model evals:** `[e.g., python tests/eval.py]`

## 3. Non-Negotiable Engineering Rules
1. **Plan before coding:** Before touching multiple files, propose a brief plan and wait for approval.
2. **Small batches:** Make small, focused changes that can be reviewed and explained by a human in a single Pull Request.
3. **Explainability:** Avoid unnecessary abstractions or dependencies. The human builder must be able to explain every line shipped.
4. **Red/Green testing:** When fixing a bug or adding core logic, write or update a test that fails before the change and passes after.
5. **Zero secrets in code:** Never hardcode API keys, tokens, or credentials. Always read from environment variables (`.env`) and update `.env.example` when new variables are needed.
6. **Stop when looping:** If a fix fails twice in a row, stop, summarize what failed, and ask the human before trying a third approach.
