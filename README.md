# 🤖 AI Email Triage Agent

An autonomous microservice designed to ingest raw communication payloads, perform multi-class intent evaluation via LLMs, prioritize context tags, and generate pre-formulated human-in-the-loop draft responses.

## 🚀 Architecture & Stack
* **Runtime:** Python 3.11, FastAPI
* **Intelligence Layer:** OpenAI GPT-4o-mini (JSON Mode structured outputs)
* **Automation Framework:** GitHub Actions (Cron execution validation)
* **Cloud Infrastructure:** GitHub Codespaces (Ephemeral container containerized execution)

## 🛠 Quick Start (Zero Local Install Required)
1. Open this repository directly in **GitHub Codespaces**.
2. Pass your `OPENAI_API_KEY` through your repository Codespace Secrets.
3. Launch the API locally inside the container:
   ```bash
   uvicorn main:app --reload --port 8000
